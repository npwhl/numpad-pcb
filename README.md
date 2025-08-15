# 6x4 USB-C Numpad PCB
A PCB for a numpad 6x4 numpad with a row for four customizable macros. Uses Alps switch footprints and a USB-C connection. Designed in Kicad.    
TBA: image here of the 3D model  
TBA: an image of the final PCB in person! :-)  
TBA: link to firmware repository   

# The Design
<img src="SchematicMain.png" alt="Schematic of the MCU" width="640"/>
_A schematic of the MCU connections._  
<img src="SchematicMatrix.png" alt="Schematic of the Switches Matrix" width="640"/>
_A schematic of the matrix of switch connections._     
TBA: multiple images of the PCB in the PCB viewer     

# How It Was Made
**Software:** Kicad EDA v9.03  
**Manufacturer:** TBA  
This numpad uses the following bill of materials:  
table...  
   
The 3D modeling software Blender has many shortcuts that are only accessable using numpad shortcuts. Although these features are also accessable on Blender's UI, these shortcuts greatly accelerate the modeling process. However, my partner's keyboard is 65% and lacks a numpad. I wanted to design him a numpad that could solve this problem while using the keycaps and Alps switches he currently had. I also wanted to design the numpad with USB-C conectivity and a 4-key macro row for any additional shortcuts.  
  
To make the numpad, I followed [Masterzen's tutorial](https://www.masterzen.fr/2020/05/03/designing-a-keyboard-part-1/) on designing a PCB for a keyboard. This was my first time designing a PCB and using software like Kicad. I initially struggled with laying out the components on the PCB. I learned a lot of new information about why PCB components are laid out in specific ways and how to handle signals with minimal noise. I also learned about the importance of impedance on especially delicate routes such as the USB-C's D+/D- differential pair.  
talk about the rest...    
TBA: a WIP image of the PCB in Kicad   

# To Do
This PCB is still in progress. The next steps are:  
1. Order PCB board and its components. 
2. Program the firmware using [QMK](https://github.com/qmk/qmk_firmware). 
3. Model a chassis for the numpad in Solidworks. 
4. Create a main repository where the final design is kept. 

# How to Build
If you want to build the numpad yourself, you can order the parts following the links on the bill of materials table above! You can also use the same manufacturer, or the following Kicad-recommended manufacturers:  
* [Alsier (US)](https://aisler.net/)
* [OSHPark (US)](https://docs.oshpark.com/design-tools/kicad/generating-kicad-gerbers/)
* [PCBWay (China)](https://www.pcbway.com/blog/help_center/Generate_Gerber_file_from_Kicad.html)

<sub><sup>PS: Thank you (bf's github user)!</sup></sub>