# M5Stack CORE2 PCB Reverse Engineering Project

<img src="Documentation/images/board-3d-view.png" width="600" alt="M5Stack CORE2 PCB 3D View">

This repository contains a reverse-engineered PCB design of the M5Stack CORE2 development board created in Altium Designer.

## Board Preview

<p float="left">
  <img src="Documentation/images/top-layer.png" width="300" alt="Top Layer">
  <img src="Documentation/images/bottom-layer.png" width="300" alt="Bottom Layer">
</p>

## Project Description

The M5Stack CORE2 is a feature-rich IoT development kit based on the ESP32 microcontroller. This project provides the PCB design files recreated through careful reverse engineering of the original board.

### Features
- ESP32-D0WDQ6 dual-core microcontroller
- 16MB Flash + 8MB PSRAM
- AXP192 power management
- Built-in battery management
- TFT LCD interface
- MPU6886 IMU
- Speaker & microphone
- USB Type-C interface
- SD card slot
- [Add any additional features you've documented]

## Repository Contents
- `M5_CORE2.PrjPcb` - Main Altium Designer project file
- `M5_CORE2_re.SchDoc` - Schematic document
- `M5_CORE2_re.PcbDoc` - PCB layout document
- `myLibs.SchLib` - Schematic library
- `myLibs.PcbLib` - PCB footprint library
- `/Outputs` - Generated output files
- `/Documentation` - Additional documentation

## Documentation

### PCB Specifications
- Layer count: 4 layers
- Board dimensions: [Add dimensions]
- Min trace width: [Add specification]
- Min via size: [Add specification]

### Layer Stack-up
1. Top Layer - Signal
2. Inner Layer 1 - Ground
3. Inner Layer 2 - Power
4. Bottom Layer - Signal

### Schematic
The complete schematic is available in PDF format here: [Schematic PDF](Documentation/M5_CORE2_Schematic.pdf)

<img src="Documentation/images/schematic-preview.png" width="600" alt="Schematic Preview">

### PCB Layout

#### Layer Stack-up Visualization
<img src="Documentation/images/layer-stackup.png" width="400" alt="Layer Stack-up">

#### Critical Component Placement
<img src="Documentation/images/component-placement.png" width="600" alt="Component Placement">

## How to Use
1. Clone this repository
2. Open the project in Altium Designer
3. All required libraries are included in the project
4. Generate outputs as needed

## Important Notes
- This is a reverse-engineered project for educational purposes
- All components and footprints have been recreated based on the original board
- [Add any special considerations or known limitations]

## License
This project is released under [Choose and specify a license]

## Disclaimer
This is an unofficial reverse-engineered design. M5Stack and its products are trademarks of their respective owners. This project is not affiliated with or endorsed by M5Stack.

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.
