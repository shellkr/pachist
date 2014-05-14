Pachist
=======

A small program written in bash to show installed package history in Arch Linux. It can be used by it's own by simply write 'pachist' on the command line or run directly after another command like 'yaourt -Syua --devel --noconfirm && pachist'. I also added a verbose prefix "pachist -v" as it can sometimes be good to show install messages.


![ScreenShot](https://raw.github.com/Almehdi/pachist/master/screenshot1.png)


Usage: pachist [options] [number of lines]

	options:

	-v			Show verbose messages
	-h			Show this help
	<number>	Rows of lines to show

The configuration file can be found at ~/.config/pachist.conf and currently holds ability to change default colors and number of lines to be shown.

