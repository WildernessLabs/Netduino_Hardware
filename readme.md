# Netduino 2 and Netduino 3 Hardware Source Files

This repo contains the schematic and PCB design files for the legacy Netduino 2 and Netduino 3 hardware:

* [Netduino 2](N2)
* [Netduino Plus 2](N2 Plus)
* [Netduino 3](N3)
* [Netduino 3 w/Ethernet](N3 Ethernet)
* [Netduino 3 w/WiFi](N3 WiFi)
 
Each directory includes: 
 * `_ASSEMBLY` Directory - Files needed of a PCB assembler to instruct their "Pick and Place" machine to assemble the components on the PCB board. Also includes the Bill of Materials (BoM) for board.
* `_FAB` Directory - Files necessary for a PCB fabricator to assembly the PCB, including the copper masks, silkscreen art, drill templates, etc.
* `[model].pdf` - A PDF of the board design schematic.
* `[model].brd` - The PCB design source file. Can be opened in Allegro Cadence, or similar.