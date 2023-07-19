# ACOPOStrak-Inkscape-Template [![License: CC BY-ND 4.0](https://img.shields.io/badge/License-CC%20BY--ND%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nd/4.0/) [![Made For B&R](https://github.com/hilch/BandR-badges/blob/main/Made-For-BrAutomation.svg)](https://www.br-automation.com)
Inkscape - Template for B&amp;R ACOPOStrak - System

Use Open Source Tool ['Inkscape'](https://inkscape.org/en/) to draw [ACOPOS-Trak-Systems](https://www.br-automation.com/en/products/versatile-transport-systems/acopostrak/)
developed by [B&amp;R](https://www.br-automation.com).

[Download the templates](https://github.com/hilch/ACOPOStrak-Inkscape-Template/releases)

![Example](./example.svg)

## Using inkscape
Use 'snap cusp nodes' to exactly place the segments and splines to wire them.

### Placing modules
Enable snapping with the "cusp nodes" type. Drag the segment by holding it in the corner and moving it until a cross with the text "Cusp node to cusp node" is displayed. The two segment borders should overlap, so that only one line is visible.

![cusp_mode](/doc/cusp_mode.png)

### Wiring
Use the Bezier curves tool (B) to draw BSpline paths to wire the segments. Set the fill color to none, only select a stroke color. 

![wiring_with_splines](/doc/wiring_with_splines.png)


## SVG templates
The drawings are in scale 10:1, but be aware that Inkscape is not a CAD program. The samples contain further information.

### X-direction
preferred direction
![xdirection](/doc/xdirection.png)
### Markers
Markers at 90 mm and 150 mm, 30 mm long
![markers](/doc/markers.png)


## Standard Guide Elements

### Straight
Contains 1 straight A segment
![straight_front](/doc/straight_front.png)
![straight_back](/doc/straight_back.png)
![straight](/doc/straight.png)


### 45°
Contains 1 curve A and 1 curve B
![45_degrees_front](/doc/45_degrees_front.png)
![45_degrees_back](/doc/45_degrees_back.png)
![45_degrees](/doc/45_degrees.png)


### 90°
Contains 1 curve A and 1 curve B and 1 circular arc
![90_degrees_front](/doc/90_degrees_front.png)
![90_degrees_back](/doc/90_degrees_back.png)
![90_degrees](/doc/90_degrees.png)


### 135°
Contains 1 curve A and 1 curve B and 2 circular arcs
![135_degrees_front](/doc/135_degrees_front.png)
![135_degrees_back](/doc/135_degrees_back.png)
![135_degrees](/doc/135_degrees.png)


### 180°
Contains 1 curve A and 1 curve B and 3 circular arcs
![180_degrees_front](/doc/180_degrees_front.png)
![180_degrees_back](/doc/180_degrees_back.png)
![180_degrees](/doc/180_degrees.png)

