# stealthFox
Clean and minimal set of changes to get Vertical Tabs and a minimal UI for daily driving Firefox.

## Description
Firefox layout created with the 2 aims

    1. Minimizing chrome area without modifying the stock Proton UX.
    2. Keep the core css changes minimal to ensure UI doesn't break after updates.

I've been daily driving this layout for more than 3 years starting from v1 build for Windows over to macOS now.
Initialy the theme was designed to be used with Tree Style Tabs (till v2). Since then though I have moved over to Sidebery so updating the theme to reflect the same.

Tested on **macOS** Sonoma using dark mode with **FFv122.0**.

## Features
1. Edge-like vertical tab design
2. Compact Sidebery Tree Layout with smooth transitions
3. Auto Hiding Sidebery Sidebar
4. Dynamic Indentation
5. Support for Tab Containers with visual identification
6. Pinned tabs
7. Compact Navbar
8. Auto Hiding Page Controls in Urlbar
9. Floating Find UI
10. Matches with stock Proton UI

## Demo
![Demo](demo.gif)

## Requirements
1. Firefox v122+
2. Sidebery extension

## How to use
1. Download/Clone this repo
2. Open about:profiles
3. Open root location for your deault profile
4. Copy chrome folder from the downloaded repo and paste it in the profile root location.
5. Import sidebery-data.json from Sidebery Settings > Help > Import addon data
