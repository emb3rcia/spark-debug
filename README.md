# spark-nas
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

© 2026 emb3rcia

Hardware: CERN OHL v2
3D & Images: CC BY 4.0
