# NER22A Electrical Schematics
This repository contains the KiCAD electrical Schematic files and Altium schematic PDFs for the NER22A FSAE vehicle. 

## File Locations
All non-PCB electrical schematics are drawn in [**KiCAD 6**](https://www.kicad.org/download/).\
Schematic files for PCBs are drawn in Altium and can be found in the [NER Altium 365 Vault](https://northeastern-fsae.365.altium.com/getstarted). 
> Note: Once a PCB has been ordered, the schematics should be printed as a PDF and put in the relevant folder in this repository.

## Schematic Organization
Nested pages should be minimized\
All custom PCBs should be implemented as components\
Use lines and 3mm text to indicate boxes\
Panel mount connectors should be crossing over box lines\
### Net Names:
Use camelCase\
**TYPE_PinName_IN/OUT**\
> Ex: TSAL_High, SPI_IM_IN, SHUTDOWN, GLV_12V

