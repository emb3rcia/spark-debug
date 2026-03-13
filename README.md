# spark-debug
# Navigation
- [About project](#about-project)
  - [Motivation for the project](#motivation-for-the-project)
  - [Humorous additions](#humorous-additions)
  - [Pin tables](#pin-tables)
  - [Development tools](#development-tools)
  - [Features](#features)
- [Images](#images)
- [License](#license)

# About project

spark-debug is simple CH347T based USB debugger and programmer.

## Motivation for the project

spark-debug was created from need for both SPI programmer and UART debugger for my other project, spark-nas

## Humorous additions

I added 2 humorous silkscreen text as this project lacks personality without them in my opinion.

## Pin tables

Pin tables on PCB's silkscreen are named based on IC pins, not on desired connection on it. This means that TX UART pin should be plugged to RX of debugged device etc.

## Directory overview

- 3D file of PCB is available in `/3D`
- KiCad project files are available in `/KiCad Project Files`
- Gerber files are available in `/Gerbers`

## Development tools

- KiCad for EDA work

## Features

- UART, I2C and SPI ports
- USB-A plug
- Integrated 3.3V LDO

# Images

Schematic

![schematic](/Images/Schematic.png)

3D viewer top side

![3d top side](/Images/Top.png)

3D viewer bottom side

![3d bottom side](/Images/Bottom.png)

# License

## PCB / Schematic License

All files in `/PCB`, `/Schematic` and `/Gerbers` folders and their subsequent subfolders are licensed under the CERN Open Hardware License v2 (Weakly Reciprocal).

See `/Licenses/CERN-OHL.txt` for full terms.

## 3D files, images and documentation License

All files in `/3D`, `/Images` and `/Docs` folders and their subsequent subfolders are licensed under the CC-BY 4.0 License.

See `/Licenses/CC-BY-4.0.txt` for full terms

# BOM

|Name                                     |Purpose                                               |Cost per unit                                                   |Amount|Total    |Link                                                        |Distributor                |
|-----------------------------------------|------------------------------------------------------|----------------------------------------------------------------|------|---------|------------------------------------------------------------|---------------------------|
|FOJAN FRC0603J472 TS                     |4.7 kOhm strap resistor (100 is minimal order)        |0.001 USD                                                       |100   |0.10 USD |https://www.lcsc.com/product-detail/C2907166.html           |LCSC                       |
|Samsung Electro-Mechanics CL10A106KP8NNNC|10uF decoupling capacitor (50 is minimal order)       |0.0065 USD                                                      |50    |0.33 USD |https://www.lcsc.com/product-detail/C19702.html             |LCSC                       |
|HRE CGA0603X7R104K500JT                  |100nF decoupling capacitor (100 is minimal order)     |0.0023 USD                                                      |100   |0.23 USD |https://www.lcsc.com/product-detail/C6119867.html           |LCSC                       |
|Littelfuse SMBJ5.0A                      |TVS Diode for VBUS trace (5 is minimal order)         |0.10 USD                                                        |5     |0.49 USD |https://www.lcsc.com/product-detail/C83333.html             |LCSC                       |
|WCH CH412K                               |TVS Diode for data traces                             |0.66 USD                                                        |1     |0.66 USD |https://www.lcsc.com/product-detail/C89184.html?s_z=n_CH412K|LCSC                       |
|MOLEX 480370001                          |USB Plug                                              |0.90 USD                                                        |1     |0.90 USD |https://www.lcsc.com/product-detail/C136455.html            |LCSC                       |
|UMW AMS1117-3.3                          |3.3V LDO (10 is minimal order)                        |0.04 USD                                                        |10    |0.37 USD |https://www.lcsc.com/product-detail/C347222.html            |LCSC                       |
|SCTF SX3M8.000B10F20TNN                  |Oscilator for internal clock                          |0.47 USD                                                        |1     |0.47 USD |https://www.lcsc.com/product-detail/C5452681.html           |LCSC                       |
|WCH CH347T                               |Translating interfaces to USB                         |3.31 USD                                                        |1     |3.31 US  |Dhttps://www.lcsc.com/product-detail/C5122332.html          |LCSC                       |
|PCB                                      |Printed Circuit Board for project (5 is minimal order)|1.42 USD                                                        |5     |7.10 USD |https://www.jlpcpb.com/                                     |JLCPCB                     |
|Shipping                                 |JLCPCB + LCSC shipping cost combined                  |N/A                                                             |N/A   |13.03 USD|N/A                                                         |Global Direct Standard Line|
|Total                                    |N/A                                                   |N/A                                                             |N/A   |18.37 USD|N/A                                                         |N/A                        |


© 2026 emb3rcia

Hardware: CERN OHL v2
3D & Images: CC BY 4.0
