# Telinkrin-GTK
a GTK2,and GTK3 file for the Gnome-desktop


## This repository only contains the Telinkrin-theme and Telinkrin shell!


![s](https://cn.pling.com/img/6/6/d/b/a3f4d4dfbb6340c0e6a75bd68d38c8c2c527.jpg)

A modern and refined re-interpretation of Ambiance for Ubuntu 18.04

Nautilus and Tweak-tool have a new and modern look. And theming is persistent to the smallest detail. Combined with the Shell-theme, background, and icon-theme it really looks consistent.

There are Youtube -videos made by Charlie Henson about these themes, so check it out:

ARRONGIN:
https://www.youtube.com/watch?v=8VUypqR1w2Y

TELINKRIN:
https://www.youtube.com/watch?v=beNz0nRcqgQ

NEW, is the color-variant Telinkrin, All with matching wallpaper, icons and shelltheme

Please, try and rate, comment. Any input or criticism is welcome.

About the shell-theme: the dock is not themed. If you use dash-to-dock, then use its settings to match the dock to your own liking. Telinkrin's shell-theme has its own teal coloring.

There is an matching iconset avaliable : Arrongin-Telinkrin-icon-themes
The iconthemes have a common but seperate downloadsection here at Gnomelook.ORG

## Issues:

You will notice that resizing the sidebar in nautilus behaves strange. This is not a bug. Visually the sidebar will not change (to keep it alligned with the headerbar), but you will still see the pointer for resizing. For this to work properly, pleas keep the sidebar-size small as possible.


## Requirements:

GTK+ 3.20 or later. Only standard (or Ubuntu) gnome-desktop is supported. Ready for Ubuntu 18.04
Disable gnome-extensions that reside on the headerbar because they mess up the headerbar-theming.

Window-buttons-layout (min/max/close) at the right side. (DO NOT PUT IT ON THE LEFT-SIDE)
No support for left-side window-controls! There will be no future support for left-sided buttons...

GTK2 ENGINES REQUIREMENT

- GTK2 engine Murrine
- GTK2 engine Pixbuf

Fedora/RedHat distros:
yum install gtk-murrine-engine gtk2-engines

Ubuntu/Mint/Debian distros:
sudo apt-get install gtk2-engines-murrine gtk2-engines-pixbuf

ArchLinux:
pacman -S gtk-engine-murrine gtk-engines

## What to do:

Extract and put it into the themes directory i.e. ~/.themes/ or /usr/share/themes/ (create it if necessary).Then change the theme via distribution specific tool like Gnome tweak tool or Unity tweak tool, etc. (If you use Snap-packages instead of app's from the normal repositories than definitely put the theme to /usr/share/themes/.
