# Thermal Lab downloads

[Download the Windows installer](https://github.com/Upgrade-Energy/Thermal-Lab-Downloads/releases/tag/v0.1.0-dev18)

Public installer downloads require no GitHub account. Windows 10/11 x64; Python is bundled. Install in the Windows account that will use the app. Existing recordings and layouts are retained.

## Camera setup

1. Install TOPDON TopView and its camera driver separately. TopView 1.30.003 is the tested version; proprietary camera libraries are not bundled in Thermal Lab.
2. Close TopView and disconnect Thermal Lab cameras in other signed-in sessions.
3. Open Thermal Lab DEV18. It automatically finds compatible TopView installations and replaces missing or inaccessible saved paths.
4. Select the camera and choose Connect camera. For a custom installation, open Camera and use Find TopView or Browse. The selected folder should contain dll/dll_c001max/libirdvs.dll.

An incompatible library is rejected with a setup message. Installing a different TopView version does not establish compatibility automatically.

## Downloads and updates

DEV18 is a development prerelease. The built-in updater currently uses the private development repository; users without access can download updates from this public repository. Each release includes a SHA-256 checksum. This repository contains release downloads and setup instructions; the development repository remains private.
