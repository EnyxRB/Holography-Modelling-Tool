# Holography-Modelling-Tool
My tool designed for creation, manipulation and exporting of holograms in Expression2 (Art of Holography)

What does it do?:
  - HOLOGRAPHY is the science and practice of making holograms
  # This tool enables a more practical way of creating and modelling detailed hologram models in Expression2.
  # Meaning you don't have to edit that same line of code over and over just to get the damn thing
  # in the right position. I've been there before. Even for the experienced holo modelers, this makes the entire process
  # massively quicker... once you know the commands...

Installation instructions:

  -Recommended:
  Download ZIP and paste entire folder into steamapps/garrysmod/garrysmod/data/expression2/e2shared.
  Why in the e2shared folder? - The software uses a bunch of file write and read functions and therefore due to wiremods coding, requires the code to be written/examined to be one of a select few chosen folders. Put it in e2shared and you will not have any problems.
  
  -Other:
  Use an SVN client such as tortoiseSVN to auto update from github. I only recommend ZIP because I have implemented my own auto update option which is completely optional, unlike SVN and will only update the files I deem important to update.

Useage Instructions:
  #1. Place the Holography Modelling Tool E2 on the ground (main/Holography_Modelling_Tool.txt)
  #2. Place the Holography Modelling Tool Slave E2 on the ground (main/Holography_Modelling_Tool_Slave.txt)
  #3. Make your creation using the commands and controls above
  #4. Remember to -save followed by a filename often so you dont loose your progress
  #4. Type -export followed by the filename you wish the E2 to have
  #5. Right click on the placed slave E2 and save it
  #6. Got yourself a holo model
  
Chat Commands:
  #   -i model : creates a new hologram with said model
  #   -delete : deletes the current hologram from the program
  #   -inc number : e.g. -inc 5. sets the incremental for the currently selected mode.
  #   -move x,y,z : moves the current hologram to given x,y,z coordinates
  #   -move reset : resets the position of the current hologram back to starting position
  #   -scale reset : resets the scale of the current hologram
  #   -scale double : doubles the current scale of the current hologram
  #   -scale half : halves the current scale of the current hologram
  #   -scale x,y,z : changes the unit scale of the current hologram to vec(x,y,z). Same as holoScaleUnits()
  #   -scalem x,y,z : changes the multplier scale of the current hologram vec(x,y,z). Same as holoScale()
  #   -ang p,y,r : changes the current angles to the said pitch,yaw and roll
  #   -ang reset : resets the angle of the current hologram to it's starting angle
  #   -color R,G,B : e.g. -color 255,0,0. changes the color of the current hologram to said color values
  #   -alpha number : changes the alpha of the current hologram to said number
  #   -mat material : changes the holograms material to the said material
  #   -mirror direction (forward/right/up) : creates a mirrored hologram around the e2 across the said plane
  #   -copy model/pos/scale/ang/color/mat/alpha : copies said value of properties of current hologram
  #   -paste model/pos/scale/ang/color/mat/alpha : pastes the last copied value onto the curent hologram
  #   -dupe : duplicates the current selected hologram in the exact same position
  #   -save name : saves the project as the given filename in the project folder
  #   -save : in the case that you have already given a filename to save as, you can use save to quick save
  #   -load name : finds and loads the project with the given filename
  #   -export filename: sets the code required to spawn your creation in the slave e2 and changes slave name to said filename
  #   -projects :  prints a list of all projects currently saved in the project folder
  
Key Controls:
  #   numpad1 = changes current mode to move mode, allowing movement with keys
  #   numpad2 = changes current mode to scale mode, allowing unit scaling with keys
  #   numpad3 = changes current mode to angling mode, allowing angling with keys
  #   numpad8 = move holo forward /pitch holo down
  #   numpad5 = move holo backward/pitch holo up
  #   numpad4 = move holo left/yaw holo left
  #   numpad6 = move holo right/yaw holo right
  #   numpad- = move holo up/roll holo left
  #   numpad+ = move holo down/roll holo right
  #   numpad/ = cycles to the previous hologram in the program
  #   numpad* = cycles to the next hologram in the program
