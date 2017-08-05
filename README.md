# Holography-Modelling-Tool
My tool designed for creation, manipulation and exporting of holograms in Expression2 (Art of Holography)

## What does it do?:
  - HOLOGRAPHY is the science and practice of making holograms
  - This tool is essentially a live 3D editor for creating and manipulating holograms. You can create/save/load projects and export them to format and create the code required to spawn your creation as normal hologram code.
  - It enables a more practical way of creating and modelling detailed hologram models in Expression2. Meaning you don't have to edit that same line of code over and over just to get the damn thing in the right position. I've been there before. Even for the experienced holo modelers, this makes the entire process massively quicker... once you know the commands...

## Installation instructions:
  
  **IMPORTANT**: You MUST paste the holography_modelling_tool folder in e2shared, not Holography-Modelling-Tool-master! If you do this incorrectly, no auto updates will work and shared files will fail!
  
  - Recommended:
  Download ZIP and copy the holography_modelling_tool folder from the master, then paste this folder into steamapps/garrysmod/garrysmod/data/expression2/e2shared.
  Why in the e2shared folder? - The software uses a bunch of file write and read functions and therefore due to wiremods coding, requires the code to be written/examined to be one of a select few chosen folders. Put it in e2shared and you will not have any problems.
  
  - Other:
  Use an SVN client such as tortoiseSVN to auto update from github. I only recommend ZIP because I have implemented my own auto update option which is completely optional, unlike SVN and will only update the files I deem important to update.

## FAQ/Debugging:

  **I get the message "No model found for this hologram, try again..." when trying to create a new hologram.** -> You must make sure the server you are playing on has wire_holograms_modelany 1 or wire_holograms_modelany 2, otherwise server/custom models cannot be spawned.

## Useage Instructions:
  - #1. Place the Holography Modelling Tool E2 on the ground (main/Holography_Modelling_Tool.txt)
  - #2. Place the Holography Modelling Tool Slave E2 on the ground (main/Holography_Modelling_Tool_Slave.txt)
  - #3. Make your creation using the commands and controls above
  - #4. Remember to -save followed by a filename often so you dont loose your progress
  - #4. Type -export followed by the filename you wish the E2 to have
  - #5. Right click on the placed slave E2 and save it
  - #6. Got yourself a holo model
  
Unsure about commands? Check the code of the tool itself to see the most up to date list of commands and keybinds.
