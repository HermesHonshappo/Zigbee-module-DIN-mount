# Zigbee module DIN mount
This is a parametric casing to mount Zigbee Modules in a eletrical panel with a DIN rail
- There is an engraved Zigbee logo on the front
- There is a slot to put a label to identify the module once the electrical panel is closed
- The front should be aligned with your regular circuit breakers.  Warning: if the module is too "wide" (see Step 2 for measurements), it may require adjustments in the electrical panel cover.
Typically, modules that are below 45mm wide should fit an electrical panel without problem.

This is designed in FreeCAD, and can then be exported to STL to print on a classic FDM 3D printer

_If you like and use this project, you can support me with the "Sponsor" button at the top of this page_<br>

## Step 1
Install FreeCAD, if you haven't done so yet
Install files can be found there: https://www.freecad.org/downloads.php

Once installed, in FreeCAD, go tools -> Addon Manager

<img width="342" alt="{2E7E60C9-C6BE-4C3E-8E1F-15B755B4C321}" src="https://github.com/user-attachments/assets/a97b61d2-1274-4621-ab26-102ab0b8c518" />

In the Addon Manager search bar, type 'DynamicData'

<img width="454" alt="{67FEA4C0-04C2-407E-B74C-7358DEA9047B}" src="https://github.com/user-attachments/assets/efaa5644-3aa7-456a-b288-bedc4adc18d5" />

Click to install, then close and relaunch FreeCAD

## Step 2
Take the measurements below on the module **in millimeters**:

![IMG_20250415_160030_HDR](https://github.com/user-attachments/assets/f886047c-c0d5-45b7-b2d9-ac74b93131f1)

![IMG_20250415_160039_HDR](https://github.com/user-attachments/assets/e64f5619-a900-4dd2-a1bf-563513e1d9de)

## Step 3
- In FreeCad, open the `Zigbee module DIN mount.FCStd` file
- On the top left, click on the section called `ddModule`
- Input the values measured in step 2 in the bottom left section

<img width="1024" alt="FreeCAD1" src="https://github.com/user-attachments/assets/7abf23fa-136a-460d-ace0-3a6359ae1770" />

The 3D model should be recomputed automatically to match the values you input.

## Step 4
- In the tree display on the top left, double click on the `Casing` object, make sure it's selected (shows in bold)

<img width="226" alt="{AD0EE09B-7839-48E2-9EFF-369EB2AE581B}" src="https://github.com/user-attachments/assets/4e5dda2b-f98e-4a0c-98c0-88361a87c69d" />

- Export the casing as an STL

<img width="210" alt="{097C7F8B-9CBA-4BA9-B712-6574B46B5AFC}" src="https://github.com/user-attachments/assets/922a00ae-b7ce-436d-ba1b-c2db7b43d424" />

## Step 5
Use this file with your usual slicer and print!

Here are 3 module casings of different sizes made with this FreeCAD file:
![IMG_20250415_165053_HDR](https://github.com/user-attachments/assets/60a47696-b7d4-4cb3-9d6b-1d62a5a76669)

# Options
## Colored inserts for the Zigbee Logo

In FreeCad, on the top left tree you can select the `LogoZigbeeInserts` object. Then export to STL as in Step 4 above.

<img width="188" alt="{D64C7A89-12E2-4EB4-A6D1-FB033AED5C36}" src="https://github.com/user-attachments/assets/57589943-6c9f-4433-852d-ca8f922ced8b" />

This can be used to print small inserts with a red material, and glue them into the grooved logo in the main casing. This way you have a perfect Zigbee logo on the front of the module!

## Adjust tolerance & thickness of the casing
- In FreeCad, on the top left, click on the section called `ddCasing`

<img width="1024" alt="FreeCAD2" src="https://github.com/user-attachments/assets/d22d99e6-2e15-413f-8fb3-3b301c2538ca" />

- in the data on the bottom left:
  - adjust the `Thickness` parameter to increase or decrease the shell thickness. By default it is 2mm
  - adjust the `Hole Compensation` depending on your 3D printer tolerance. By default, it is 0.2mm
If the module is too loose in the casing, decrease this value. If the module has trouble getting in the casing, increase this value
**Before you do this, please check your module measurements!**
