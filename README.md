# Dom's Dotfiles

## Description
This repo contains the configuration files I use on my current system.

## System Configuration Overview
My system currently uses an i3-gaps as a window manager.
This is actually my first build using i3-gaps instead of i3 and honestly, it's starting to grow on me.

i3bar has been replaced with polybar for improved functionality and better aesthetics.

Dunst is used as my notification manager so Spotify can be used without borking the WM.

My .xinitrc is currently minimally configured to select random images of Fjords and assign them to each monitor's background individually.
xinitrc also instantiates i3-gaps and loads .Xresources.

Speaking of .Xresources, upon being loaded by .xinitrc, xrvt-unicode loads a custom color scheme and becomes significantly less ugly!
Which does not say much given its default color scheme is like having a staring contest with a flashbang.
Once the colorscheme loads, some sneaky perl scripts get loaded at the very bottom to enable copy-paste functionality which the xrvt-unicode devs didn't feel was very important.

How fun is that!
