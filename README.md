# README

## Overview

This is just a specific `awesomewm` configuration that works well on ArchLinux.

When DE tools can be used we opt for XFCE4 applications.  This configuration is developed on Arch Linux.

**Status:** it works, but could be fine tuned more.

## Installation

Clone into `$XDG_CONFIG_HOME` directory or `$HOME/.config`:

```
cd $HOME/.config
git clone https://github.com/Kulak/bawesome.git awesome
cd awesome
git submodule init
git submodule update
```

## Screenshots

- [on screen help](doc/images/on-screen-help.png)
- [run application](doc/images/rofi.png)
- [clipboard manager](doc/images/clipboard-manager.png)
- [active window](doc/images/active-window.png)

## Features

### Blue Color Scheme

The color scheme is just a copy of default scheme with tweaks to improve usability.

The color scheme uses classic blue color to indicate window in focus.  It uses blue window border for focused window.  This visually connects "taskbar" area with window border and makes it more intuitive to identify focused window.

Non-focused windows are of darker blue color.

Minimized windows have dark background.

Keyboard shortcuts text in Help dialog window is readble. 

### XFCE4 Screenshooter

Mapped nice XFCE4 screenshot taking application to standard set of Print Scr key combinations.

### Better Launcher

Use of "rofi" as launcher, because it is easy to see and to read.  Default launcher steals focus and its focus can be easily missed.

### Alt-Tab Window Switcher

"rofi" is used as Window Switcher and matches standard "Alt-Tab" keyboard shortcut.

### Standard Extended Keys are Mapped

Keyboard volume management keys (up, down and mute toggle) are properly mapped via `pactl`.

Monitor brightness control keys are mapped.

### Battery Power Widget

Requires loading GIT submodule.

## External Dependencies

References are to Arch Linux packages.  Use "Upstream URL" on corresponding package pages to identify actual application dependency for your Linux distribution.

1. [alacritty](https://archlinux.org/packages/community/x86_64/alacritty/)
2. [vim](https://archlinux.org/packages/extra/x86_64/vim/)
3. [rofi](https://archlinux.org/packages/community/x86_64/rofi/)
4. [xfce4-screenshooter](https://archlinux.org/packages/extra/x86_64/xfce4-screenshooter/)
5. [pactl](https://archlinux.org/packages/extra/x86_64/libpulse/) to raise and reduce volume
6. [xbacklight](https://archlinux.org/packages/extra/x86_64/xorg-xbacklight/)
