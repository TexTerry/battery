# Battery

Battery is a script written in bash-script that shows the current battery power
as percentage and a fancy colored bar.
Battery is tested on Macs running Mac OS X 10.8.5, but it should run on every
system that provides the *ioreg*-command.

## Features

* Display the current battery power nummericaly
* Display the current battery power as bar both colored and in the terminal
  default color.
* User defined bar-width.

## Usage

For a simple uncolored bar call the programm without options.
If you like it fancy, you could use one of this options:

	-h              Output a short help
	-c              Output is colored
	-w <no>	        Define the width of the bar (default: 20)
	-n              Output a numerical value only (may be usefull in your own scripts

## Conclusion

I wrote Battery for my own needs. It is one of my first Bash-scripts (exept
some dozen 3-liners). If it is usefull for you, I would be delighted to hear
about that. Feel free to send me an e-mail to
 [marcel.duemmel@gmail.com](marcel.duemmel@gmail.com).
