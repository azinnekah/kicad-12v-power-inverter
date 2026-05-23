*PCB Project 1: 12V Power Inverter - Adam Zinnekah 5/20/26*
*Inspired by @diyhideout on their mini inverter.*
*Circuit topology based on standard reference application schematics for the IR2153 Half-Bridge gate driver.*
**Circuit has passed DRC gates in KiCad but has not been manufactured nor tested. Preparing the Gerber files for potential fabrication in the future.**



*This layout PCB is an introduction to the KiCad EDA workflow, from schematic capture, objection creation and implementation, PCB design and 3D modelling, and route-tracing.*

**Tweaks I have made to the design and why**

**Widended Power Delivery Top Rails**
*Expanded the 0.4mm trace width to 1.5mm to prevent potential parasitic voltage drops and preventing board delamination.*

**Replaced potentiometer from acptechnologies CA6 unit that was recommended to Bourns 3296W Vertical 3-pin**
*Bourns pot had 3d project files built-in to KiCad workspace, and provides more precision tuning for resistance values to control the RC time constant.*
