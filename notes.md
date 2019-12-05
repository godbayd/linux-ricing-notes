# Ricing Notes

## Start x problems
startx works once after proper configuration but after reboot will not work. 
In order to get it to work again, xorg needed to be removed and reinstalled, to work 
only once again.

https://unix.stackexchange.com/questions/260731/how-to-install-xorg-inside-virtualbox-guest

had to pacman -S xorg virtualbox-guest-utils

this got things working consistently at least so far

## Xresource Color Schemes

in setting colors there are multiple to set
 color0, color1, color2, etc...
 
To see what each of the colors are, run neofetch
The colors in the pallet bar below the info correspond with the color
settings in .Xresources in respective order
