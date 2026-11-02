# Omni-Fab 

> *Make Innovation Tangible.*

**Empowering Innovation Through Open Engineering.**

Technology, at its most fundamental level, is the extension of human agency through tools. When tools are open and documentation is transparent, understanding, creation, and innovation become an accessible universal dialogue.

Omni-Fab is an open-source engineering ecosystem dedicated to making advanced manufacturing an open platform for innovation. Committed to developing hardware under the CERN Open Hardware Licence v2 and software under the GNU General Public License v3.0, Omni-Fab is built on the foundational idea that real innovation is born from rigorous engineering done by everyday people and made possible through complete, open documentation and collaboration so any researcher, business, or independent innovator can adapt, repair, and create.

## A Modular Architecture

Omni-Fab's long-term architecture encompasses three distinct realms of manufacturing, developed as an interconnected, modular machine ecosystem:

1. [![5-Axis CNC Milling](https://img.shields.io/badge/5--Axis_CNC_Milling-bf9000?style=for-the-badge)](#)

   [**Open-CNC**](https://github.com/Omni-Fab/Open-CNC) powered precision subtractive machining for machine structural foundations and components with complex geometries:
   - **Structural machine components**
   - **Precision reference surfaces**
   - **High-vacuum system components**
   - **Custom device/HMI enclosures**

2. [![Maskless Semiconductor Integrated Circuit Fabrication](https://img.shields.io/badge/Maskless_Semiconductor_Integrated_Circuit_Fabrication-351c75?style=for-the-badge)](#)

   Automated IC fabrication designed to feed directly into downstream PCB assembly utilizing four core processes:
   - **Thin-Film Deposition** (Adding material layers)
   - **Multi-E-Beam Direct-Write Lithography** (Patterning circuits)
   - **Selective Etching & Planarization** (Shaping and flattening)
   - **Advanced Packaging & Die Preparation** (Interconnects, dicing, and encapsulation)

3. [![FR4 PCB Fabrication & SMT Assembly](https://img.shields.io/badge/FR4_PCB_Fabrication_%26_SMT_Assembly-38761d?style=for-the-badge)](#)

   Custom automated printed circuit board manufacturing and combined automated surface-mount component placement and soldering for complete electronic fabrication capability:
   - **Substrate Structuring & Drilling** (Patterning traces and through-holes)
   - **Via Metallization & Surface Finishing** (Layer interconnects and pad passivation)
   - **Automated SMT Dispensing & Placement** (Solder application and component pick-and-place)
   - **Thermal Reflow & Joint Inspection** (Solder profiling and automated visual verification)

## Conclusion

By modularizing these disciplines into open reference implementations, Omni-Fab aims to lay the groundwork for a future where the tools to build are as limitless as what we choose to create. This begins with the motion-control foundations of [**Open-CNC**](https://github.com/Omni-Fab/Open-CNC) and its first implementation, 5XM: a precision five-axis desktop CNC milling machine.

**P.S.** I realize how complex and interdisciplinary this all is and I'm not claiming to be anywhere close to the final ambition; however, everything has to start somewhere and for this project, this is it. If you're as excited about this as I am and want to make it happen, feel free to help where you can. There are many domains that require expertise and multiple different sub projects that all probably deserve their own directory. My current focus is Open-CNC and linking CERN OHL v2 Strong license compatible hardware and GPL v3 compatible software to their own directory in the respective repos of this org.
