# dotfiles
In case you want to be as cool as I am (or my btrfs crashes again and I need to recreate my dotfiles :/)

![Screenshot of the desktop (mind that the conky config in this repo is newer than my local config)](https://i.imgur.com/gSUHfmK.png)

## Requirements
### ❤️ Core functionality
- xorg
- i3-gaps (and all dependencies like i3bar)
- feh
- picom (with experimental backend support, maybe only in AUR)
- i3status-rust (with material icons)
- conky
- xbanish
- dunst
- dmenu2
- urxvt -> rxvt-unicode
- Iosevka font

➡️ To install all needed packages on Arch Linux:
```bash
# pacman -S xorg i3-gaps feh picom i3status-rust conky xbanish dunst rxvt-unicode
# yay -S dmenu2 ttf-iosevka ttf-material-icons-git
```
(YAY is a package manager for AUR, if you don't know what I'm trying to do here.)


### ✨ For full functionality
- firefox/qutebrowser (awww)
- cmus
- pulsemixer
- htop
- nvtop
- thunar (you may want to install gvfs, too!)

➡️ To install all extra packages for full functionality on Arch Linux
```bash
# pacman -S firefox qutebrowser cmus pulsemixer htop nvtop thunar
```
(Of course you'll instantly install uBlock Origin and Privacy Badger in Firefox or I'll personally kill you with a rusty spoon.)


### Stuff you'll have to do yourself
If you really want to finish off the purple-pink look of my desktop, then use this background: [https://unsplash.com/photos/u8Jn2rzYIps](https://unsplash.com/photos/u8Jn2rzYIps)

Set the background in the end of the i3 config file (`.config/i3/config`) at the feh command and you're done. Enjoy the magic! ✨


## Thank you!
Thanks to all those awesome people who made this software and my desktop possible. Linux desktop wouldn't be as cool as it is without all of these packages! <3
