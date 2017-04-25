# Legacy Netduino 2 and Netduino 3 Hardware Source Files

This repo contains the schematic and PCB design files for the legacy Netduino 2 and Netduino 3 hardware:

* [Netduino 2](N2)
* [Netduino Plus 2](N2_Plus)
* [Netduino 3](N3)
* [Netduino 3 w/Ethernet](N3_Ethernet)
* [Netduino 3 w/WiFi](N3_WiFi)
 
Each directory includes: 
 * `_ASSEMBLY` Directory - Files needed of a PCB assembler to instruct their "Pick and Place" machine to assemble the components on the PCB board. Also includes the Bill of Materials (BoM) for board.
 * `_FAB` Directory - Files necessary for a PCB fabricator to assembly the PCB, including the copper masks, silkscreen art, drill templates, etc.
 * `[model].pdf` - A PDF of the board design schematic.
 * `[model].brd` - The PCB design source file. Can be opened in Allegro Cadence, or similar.

 
 
# License
Copyright 2017, Wilderness Labs Inc.
    
    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at
    
      http://www.apache.org/licenses/LICENSE-2.0
    
    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
