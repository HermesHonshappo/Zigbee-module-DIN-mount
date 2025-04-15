# Zigbee-module-DIN-mount
This is a parametric casing to mount Zigbee Modules in a eletrical panel with a DIN rail

This is designed in FreeCAD, and can then be exported to STL to print on a classic FDM 3D printer

## Step 1
Install FreeCAD, if you haven't done so yet
Install files can be found there: https://www.freecad.org/downloads.php

Once installed, in FreeCAD, go tools -> Addon Manager

<img width="342" alt="{2E7E60C9-C6BE-4C3E-8E1F-15B755B4C321}" src="https://github.com/user-attachments/assets/a97b61d2-1274-4621-ab26-102ab0b8c518" />

In the Addon Manager search bar, type 'DynamicData'

<img width="454" alt="{67FEA4C0-04C2-407E-B74C-7358DEA9047B}" src="https://github.com/user-attachments/assets/efaa5644-3aa7-456a-b288-bedc4adc18d5" />

Click to install, then close and relaunch FreeCAD

## Step 2
Take the measurements below on the module **in millileters**:

![IMG_20250415_160039_HDR](https://github.com/user-attachments/assets/e64f5619-a900-4dd2-a1bf-563513e1d9de)

![IMG_20250415_160030_HDR](https://github.com/user-attachments/assets/f886047c-c0d5-45b7-b2d9-ac74b93131f1)

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


<img width="1024" alt="FreeCAD2" src="https://github.com/user-attachments/assets/d22d99e6-2e15-413f-8fb3-3b301c2538ca" />
