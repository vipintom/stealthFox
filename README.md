# stealthFox
Clean and minimal set of changes to get Vertical Tabs in Firefox.

## Description
Firefox layout created with the aim of minimizing chrome area without modifying the stock Proton UX. Another goal was to keep the chore css changes minimal to ensure things don't keep breaking down after updates. Inspired after using [FlyingFox](https://github.com/akshat46/FlyingFox). Currently only supported with dark mode.

## Features
1. Auto Hiding TST Sidebar.
2. Compact TST Tree Layout.
3. Compact Navbar.
4. Auto Hiding Page Controls in Urlbar.
5. Floating Find UI.
6. Matches with stock Proton UI.

## Demo
![Demo](WYWjpZQfOJ.gif)

## Screenshots
Closed Tabbar
![Closed Tabbar](https://i.imgur.com/gFfgmcR.png)
Open Tabbar
![Open Tabbar](https://i.imgur.com/BYw4Gg2.png)
Show Page Control on Hover
![Show Page Control on Hover](https://i.imgur.com/qxXSZyt.png)
Floating Find UI
![Floating Find UI](https://i.imgur.com/JjlEHFu.png)

## Requirements
1. Firefox v92+ (tested on v93.0.2 beta with dark mode and compact layout enabled on Win10).
2. Tree Style Tabs extension.

## How to use
1. Copy/Clone this repo.
2. Open `about:profiles`.
3. Open root location for your default profile.
4. Copy `chrome` folder from the downloaded repo and paste it in the profile root location.
5. Copy `user.js` to your default profile folder.
6. Import `tst_config.json` from Tree Style Tabs settings.
