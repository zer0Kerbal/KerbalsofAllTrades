---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---
<!-- ManualInstallation.md v1.1.8.1
Kerbals of All Trades (KOAT)
created: 01 Oct 2019
updated: 29 Jul 2022 -->

<!-- this file CC BY-ND 4.0 by zer0Kerbal -->
<!-- based upon work by Lisias -->

# Kerbals of All Trades (KOAT)

[Home](./index.md)

This addon will let your kerbals have many more skills than typically given

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `exodussolis` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/exodussolis/KerbalsofAllTrades`
* Extract the package's `exodussolis/` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/exodussolis` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/exodussolis/KerbalsofAllTrades`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/exodussolis/KerbalsofAllTrades`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/exodussolis/KerbalsofAllTrades`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [exodussolis]
      + [KerbalsofAllTrades]
        + [Agencies]
          ...
        + [Compatibility]
          ...
        + [Config]
          ...
        + [Contracts]
          ...
        + [Flags]
          ...
        + [Localization]
          ...
        + [Parts]
          ...
        + [Plugins]
          ...
      * #.#.#.#.htm
      * Attributions.htm
      * CC-BY-ND-4.0.txt
      * changelog.md
      * ManualInstallation.htm
      * KerbalsofAllTrades.version
      * readme.htm
      ...
    ...
    * ModuleManager.ConfigCache
  * KSP.log
  ...
```

### Dependencies

* none
