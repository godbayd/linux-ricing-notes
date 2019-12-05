# Ricing Notes

## Start x problems
startx works once after proper configuration but after reboot will not work. 
In order to get it to work again, xorg needed to be removed and reinstalled, to work 
only once again.

https://unix.stackexchange.com/questions/260731/how-to-install-xorg-inside-virtualbox-guest

had to pacman -S xorg virtualbox-guest-utils

this got things working consistently at least so far
