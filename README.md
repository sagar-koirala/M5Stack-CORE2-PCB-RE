# M5Stack CORE2 PCB Reverse Engineering Project
This repository contains a reverse-engineered PCB design of the M5Stack CORE2 development board created in Altium Designer.
<img src="Documentation/images/board-3d-view.png" width="600" alt="M5Stack CORE2 PCB 3D View">

## Board Preview

<p float="left">
  <img src="Documentation/images/top-layer.jpg" height="300" width="300" alt="Top Layer">
  <img src="Documentation/images/bottom-layer.jpg" height="300" width="300" alt="Bottom Layer">
</p>

## Repository Contents
- `M5_CORE2.PrjPcb` - Main Altium Designer project file
- `M5_CORE2_re.SchDoc` - Schematic document
- `M5_CORE2_re.PcbDoc` - PCB layout document
- `myLibs.SchLib` - Schematic library
- `myLibs.PcbLib` - PCB footprint library
- `/Documentation` - Images and Schematic files

## Documentation

### PCB Specifications
- Layer count: 4 layers
- Board dimensions: 48 x 49.5 mm
- No. of components: 165

### Layer Stack-up
1. Top Layer - Signal
2. Inner Layer 1 - Ground
3. Inner Layer 2 - Power
4. Bottom Layer - Signal

### Schematic
The complete schematic is available in PDF format here: [`Schematic PDF`](Documentation/M5_CORE2_Schematic.pdf)

[<img src="Documentation/images/schematic-preview.jpg\" width="600" alt="Schematic Preview">](Documentation/M5_CORE2_Schematic.pdf)

## PCB Layout
<p float="left">
    <p float="left">
        <figure style="display: inline-block; margin: 1px;">
            <img src="Documentation/images/m5Layout_top.jpg" height="300" width="300" alt="Top Layer">
            <figcaption>Top Layer</figcaption>
        </figure>
        <figure style="display: inline-block; margin: 1px;">
            <img src="Documentation/images/m5Layout_Gnd.jpg" height="300" width="300" alt="Inner Layer 1">
            <figcaption>Inner Layer 1 - Ground</figcaption>
        </figure>
        <figure style="display: inline-block; margin: 1px;">
            <img src="Documentation/images/m5Layout_pwr.jpg" height="300" width="300" alt="Inner Layer 2">
            <figcaption>Inner Layer 2 - Power</figcaption>
        </figure>
        <figure style="display: inline-block; margin: 1px;">
            <img src="Documentation/images/m5Layout_bottom.jpg" height="300" width="300" alt="Bottom Layer">
            <figcaption>Bottom Layer</figcaption>
        </figure>
    </p>

## How to Use
1. Clone this repository
2. Open the project in Altium Designer
3. All required libraries are included in the project
4. Generate outputs as needed

## Important Notes
- This is a reverse-engineered project for educational purposes
- All components and footprints have been recreated based on the original board
- [Add any special considerations or known limitations]

## Disclaimer
This is an unofficial reverse-engineered design. This project is not affiliated with or endorsed by M5Stack.