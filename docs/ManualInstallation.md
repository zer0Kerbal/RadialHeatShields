---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
# layout: bare
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- ManualInstallation.md v1.1.7.0
Radial Heat Shields (RHS)
created: 01 Oct 2019
updated: 18 Apr 2022 -->

<!-- based upon work by Lisias -->

# Radial Heat Shields (RHS)

[Home](./index.md)

Tired of blowing up? Use Radial Heat Shields by Orion Space Industries. For Kerbal Space Program.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the OrionSpaceIndustries folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/OrionSpaceIndustries/RadialHeatShields`
* Extract the package's `OrionSpaceIndustries/` folder into your KSP's GameData as follows:
  * `<PACKAGE>/OrionSpaceIndustries` --> `<KSP_ROOT>/GameData/`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/OrionSpaceIndustries/RadialHeatShields`

### If Downloaded from SpaceDock / GitHub / other

To install, place the GameData folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/OrionSpaceIndustries/RadialHeatShields`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/OrionSpaceIndustries/RadialHeatShields`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [OrionSpaceIndustries]
      + [RadialHeatShields]
        + [Agencies]
          ...
        + [Assets]
          ...
        + [Compatibility]
          ...
        + [Flags]
          ...
        + [Localization]
          ...
        + [Parts]
          ...
        * 0.9.99.0.htm
        * CC-BY-SA-4.0.txt
        * changelog.md
        * readme.htm
        * RadialHeatShields.version
      ...
    ...
  * KSP.log
  ...
```

### Dependencies

* none
