Pachist
=======

A small program written in bash to show installed package history in Arch Linux. It can be used by it's own by simply write 'pachist' on the command line or run directly after another command like 'yaourt -Syua --devel --noconfirm && pachist'. I also added a verbose prefix "pachist -v" as it can sometimes be good to show install messages.


![ScreenShot](https://raw.github.com/Almehdi/pachist/master/screenshot1.png)


Usage: pachist [options] [number of lines]

	options:

	-d, --date              Search by date
	-h, --help              Show this help
	-n, --num               Show line numbers
	-p, --package           Show output about a specific package
	-q, --quiet             Show less information
	-v, --verbose           Show verbose messages
	-V, --version           Show current version
	    --warn              Not as verbose, just warning messages
	<number>                The number of lines to show
                                
        Numbers also have support to show range of lines. The syntax is either <n> for 
        total number of lines or <n>,<n> for a range were the first number before the 
        comma tells which line from the bottom to start with and the number after the 
        comma describes the total number of lines to show. It can be very usefull 
        together with the -q flag.


The configuration file can be found at ~/.config/pachist.conf and currently holds ability to change default colors and number of lines to be shown.

![ScreenShot](https://raw.github.com/Almehdi/pachist/master/screenshot2.png)

![ScreenShot](https://raw.github.com/Almehdi/pachist/master/screenshot3.png)
