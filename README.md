# STM32-L432-projects
by La Hai Nam
# Overview
All projects in this repository are currently part of projects I have done for my college. In the future more projects will be added both college and home projects.
# Documentation (only in german)
For a brief documentation on how my projects were made refer to the documents folder. 
# Building the Code

The first 3 projects "blinky", "helloworld" and "morsecode" were coded in linux with the use of the software STM32CubeMX to create the STM32 framework with a makefile. To deploy the code enter the designated project and enter "make". Afterwards copy the "name_of_project".bin file in the newly made build folder to your STM32 board.  
Example: 
-  "cd blinky"
-  "make"
-  "cp build/blinky.bin /media/mrmr/NODE_L432KC" where blinky is the desired project and mrmr is the name of your computer.
