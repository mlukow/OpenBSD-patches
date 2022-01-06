# OpenBSD-patches
Assorted patches, work very much in progress

## In th repository

### cwm-magnet.diff

Add window-tile-{up,up-right,right,down-right,down,down-left,left,up-left} functions that fill halves and quarters of the screen with the current window, Magnet.app-like

![cwm-magnet demo](assets/cwm-magnet.gif)

### cwm-hide-groups-when-cycling.diff

Adds function that cycles between window groups, keeping window focus in each group.

### cwm-rounded-corners.diff

Adds rounded corners to windows. You can set the desired corner radius in your cwmrc file.

### cwm-menu-hint.diff

Adds `WM_CLASS`  and `WM_NAME` hint to the menus, making it possible to style them with compositors, such as picom or compton. Both values default to the `wm` property value (CWM).

### cwm-menu-customization.diff

Adds a multitude of options to customize the look and feel of the menus.

![cwm-menu-customization](assets/cwm-menu-customization.png)

### ksh-ignorecase.diff

Adds new `ignorecase` property which, when enabled, makes tab completions case insensntive
