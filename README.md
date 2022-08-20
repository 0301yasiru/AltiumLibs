# Schematic and PCB liblaries for Altium
This is an **open-source** project for my fellow electronic engineers. I have collected every component I created for my projects. You can freely use these libraries for your project without beginning from scratch. If you want to contribute to this project send me a message to add you as a collaborator.

## How to use?
The usage is very simple. You have to clone the repository to your local computer. Then inside the cloned repository, you will find a folder named **Integrated_Lib_Versions**. Inside that, there will be all the versions of integrated libraries. Copy the latest one and paste it into your Altium project folder. In Altium, go to **Project Manager > "*Your_Project*" > Add exiting to project > Select Integrated Library.**

To clone the repository, use a command line window and navigate to the location where you would like to download the repository. Then use below command to clone it.

> git clone https://github.com/0301yasiru/AltiumLibs.git


## Check List for component creation
This checklist will help you to create a complete component. Before you push into the main branch, please go through each component and check for mistakes and missing steps using this checklist. 

***For Schematic Symbol***

 - [ ] Check for duplicates.
 - [ ] Find the component from the manufactures site.
 - [ ] Check supply status and read the datasheet.
 - [ ] Update the **Designator** and **Comment** sections.
 - [ ] Rename the pins correctly.
 - [ ] Organize and group the pins for easier use.

***For PCB footprint***

 - [ ] Make sure pad sizes are slightly bigger than pins.
 - [ ] Check the clearance between pads.
 - [ ] Organize the Overlay Layers (Keep it neat)
 - [ ] Add the Assembly notes (Mechanical 24)
 - [ ] Add the 3D Model (Mechanical 1)
 - [ ] Add Keep out region (Keep out Layer)
 - [ ] Add **.Designator** thing (in Assembly Notes)
 - [ ] Mark the 1st Pin on assembly notes and overlay layers.
 - [ ] Double check PIN numbers and correct overlapping of the 3D model

***Final Checks for Both Footprint and Symbol***

 - [ ] Double check pins numbers .
 - [ ] Add the footprint for the schematic symbol.
