# Qanba JCV8 square actuator mod

## Attribution

The following text must be included in any distribution of derivatives of this file. All Links must also be included.

Copyright 2024, 2026 [Hawkeye](https://github.com/CapnHawke)

[Licensed under CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

Changes from the original design:
 - list any changes you make here

## Summary

Files are hosted here for creation of four different actuators designed to fit in Qanba Gravity levers. First, there is a square actuator, and second, there is a series of round actuators including a replacement for anyone who has lost their original actuator, and two models that are oversize in +0.5mm diameter and +1mm diameter sizes. 

The square actuator was designed for use in the Qanba Gravity JCV8 "Cherry" module lever. I have heard mixed feedback on installing this actuator in the JOV8 and JOV8S modules. It was not designed for those modules, and if you choose to install the square actuator in a JOV8 module, your results might vary. 

The round actuator was tested in a JCV8 module, but the replacement part is identical in the JCV8 and JOV8 modules. Prior to publication, these files were given to someone who had a JOV8 module lever and immediate reports back suggested that the round actuators were compatible with it. I have not personally tested it. 

## Square Actuator

The Qanba JCV8 is a lever that uses Cherry Speed Silver switches. The stems of the switches are narrow, and the spacing between the switches is wide. The actuator included with the joystick is round. As a result, the actuator cannot depress two adjacent switches simultaneously, unless it travels very deep into the diagonal. On a Qanba square gate, for example, a diagonal input cannot be pressed unless the actuator is contacting the corner of the gate. Reaching diagonal inputs requires an extremely high level of precision and necessitates contacting the gate. This results in a less user-friendly experience. 

The actuator in this repository aims to fix this problem by changing out the round design for a square design. This square actuator is able to more easily depress two adjacent at the same time. As a result, diagonal inputs are greatly increased, making it much easier for a player to reach their diagonal inputs. 

Additionally, the inner diameter of this actuator is very slightly increased, meaning that it fits less tightly on the lever shaft. This allows the shaft to rotate without twisting the actuator, and keeps the actuator aligned perpendicular to the switch stems.

## Print instructions for Square actuator

- Printed on a Bambulabs P1S
- Bambu Lab P1S 0.4 nozzle
- Textured PEI Plate
- Bambu PLA

Object/Part Settings:
- Layer Height = 0.2mm
- Wall loops = 2
- Infill Density = 15%
- Support = yes
- Brim = Auto
- Outer wall speed = 200

Quality:
- Layer Height = 0.2mm
- Initial Layer Height = 0.2mm
- Default Line width = 0.42mm
- Initial Layer = 0.5mm
- Outer wall = 0.42mm
- Inner wall = 0.45mm
- Top Surface = 0.42mm
- Sparse infill = 0.45mm
- Internal solid infill = 0.42mm
- Support = 0.42mm

Seam:
- Seam position = Aligned
- Seam gap = 15%
- Wipe speed = 80%

Precision:
- Slice gap closing radius = 0.049mm
- Resolution = 0.012mm
- Arc fitting = yes
- X-Y hole compensation = 0mm
- X-Y contour compensation = 0mm

- Ironing type = no ironing
- Wall generator = Classic

Advanced:
- Order of walls = inner/outer
- Print infill first = unchecked
- Bridge flow = 1
- Thick bridges = unchecked
- Top surface flow ratio = 1
- Initial layer flow ratio = 1
- Only one wall on top surfaces = Top Surfaces
- Top area threshold = 100%
- Only one wall on first layer = unchecked
- Detect overhang walls = yes
- Avoid crossing wall = unchecked

Supports:
- Enable support = yes
- Type = normal(auto)
- Style = Default
- Threshold angle = 30
- On build plate only = unchecked
- Remove small overhangs = yes
- Raft layers = 0

## Visual guide information for Square Actuator

Below is a render of the acutator.
![Squareish Actuator render](https://github.com/CapnHawke/Game-Controller-Parts/blob/main/Lever%20mods/images/image.png)

Below is an example image of the actuator installed in a JCV8, prior to screwing the gate back on. 
![Actuator installed](https://github.com/CapnHawke/Game-Controller-Parts/blob/main/Lever%20mods/images/IMG_7519.jpg)

## Round Actuator information

A 3mf file has been uploaded into the repository. This 3mf file was created using Bambu studio. The STLs themselves were created by exporting from Fusion. The 3mf file contains all three models, as well as some embedded text information to help identify which STL is which. 

Below is a render of the three actuators in the slicer:
![Replacement and oversize actuators](https://github.com/CapnHawke/Game-Controller-Parts/blob/main/Lever%20mods/images/Qanba%20replacement%20and%20oversize.png)

During testing, I felt that the +0.5mm actuator greatly improved my experience with the lever. Cardinal directions were snappy and immediately responsive, while diagonal directions were much easier to reach compared to the stock actuator. 

In testing, +1mm shrunk the deadzone significantly, to the point where even the slightest movement of the balltop would cause the lever to register an input. In order to consistently and reliably reach cardinal directions with this lever, users may find it necessary to slow down, or use a higher tension spring to guide themselves back to neutral more reliably. Otherwise, the travel time past the dead zone is so fast that cardinal directions could be skipped in less than 1/60th of a second. The resulting operation is the nearly-instantaneous output of the opposite cardinal direction, similar to the possible outputs on an all-button controller or keyboard in which the user can quickly execute inputs without traveling past a neutral zone. However, careless use has a high risk of accidental inputs caused by deflection of the lever past the pivot point. Users may need to modify their method of play if they wish to use this actuator effectively.

## Disclaimer
These files and instructions are provided as-is, and without warranty. Your results may vary, and by using these files and instructions, you assume the risks associated with that activity. 