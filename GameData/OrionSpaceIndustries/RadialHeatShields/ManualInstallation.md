---
permalink: /ManualInstallation.html
title: ManualInstallation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
# layout: bare
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- ManualInstallation.md v1.1.1.0
Radial Heat Shields (RHS)
created: 01 Oct 2019
updated: 27 Mar 2022 -->

<!-- based upon work by Lisias -->

# Radial Heat Shields (RHS)

Tired of blowing up? Use Radial Heat Shields by Orion Space Industries. For Kerbal Space Program.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the GameData folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/RadialHeatShields`
* Extract the package's `RadialHeatShields/` folder into your KSP's as follows:
  * `<PACKAGE>/SimpleConstruction` --> `<KSP_ROOT>/GameData/RadialHeatShields`
    * Overwrite any preexisting file.

### If Downloaded from SpaceDock / GitHub / other

To install, place the GameData folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/RadialHeatShields`
* Extract the package's `GameData/RadialHeatShields` folder into your KSP's as follows:
  * `<PACKAGE>/GameData/RadialHeatShields` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting file.

## The following file layout must be present after installation

```
<KSP_ROOT>
  [GameData]
    [RadialHeatShields]
      [Agencies]
        ...
      [Assets]
        ...
      [Compatibility]
        ...
      [Flags]
        ...
      [Localization]
        ...
      [Parts]
        ...
      [Plugins]
        ...
      0.9.99.0.htm
      CC-BY-SA-4.0.txt
      changelog.md
      readme.htm
      RadialHeatShields.version
    ...
  KSP.log
  ...
```

### Dependencies

* none