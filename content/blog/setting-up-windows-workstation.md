---
title: "Setting up a Windows laptop/workstation"
date: 2022-10-21T21:34:58+02:00
draft: true
---

In this post I will share how I set up a Windows-based workstation to my liking.

Setting up any system consists of the following 3 aspects: Software, Settings, Data.

I am following the following flow:

0. [BIOS (UEFI) settings](#0-bios-uefi-settings)
1. [Install Windows, install drivers, do Windows updates]
2. [Basic Windows cleanup, configuration and customisation]
3. [Installing 3rd party software, configuring that software]

## 0. BIOS (UEFI) settings

If you are configuring a laptop the following things are important:

- Set up a bios password so that nobody except you messes with your BIOS settings
- Disable Legacy boot (also called CSM boot, or "UEFI-only boot")
- Make sure Secure Boot is enabled and the Windows keys are in the db
- Thinkpads: swap the function and ctrl keys (personal preference)

## 1. Install Windows, install drivers, do Windows updates

1. Installing Windows 10
   - always use "basic install", or "limited experience" in order to create a local account, NEVER create a Microsoft account
   - decline all location services, decline all telemetry in the installer
2. Let Windows update search for all missing drivers, check using device manager if there are no missing
   - Thinkpads: install the "Lenovo Vantage" app using the Windows Store(🤮)
   - Update to the latest BIOS
3.

## 2. Basic Windows cleanup, configuration and customisation

use winget to install all Microsoft bloat
`winget list`
`winget uninstall <package-name>`

todo: create a script for this.

2. Settings/Preferences
   - Windows preferences
   - Windows settings
   - application preferences (context menu options)
3. Data

- telemetry must be disabled

##
