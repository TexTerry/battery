# Battery

Battery is a bash-script that shows the current battery power
as percentage and a fancy colored bar.
Battery is tested on Macs running Mac OS X 10.8 to MacOS 11.4, but it should run on every
system that provides the `ioreg`-command.

## Features

* Display the current battery power nummerically
* Display the current battery power as bar both colored and in the terminal
  default color.
* User defined bar-width.

## Usage

For a simple uncolored bar call the programm without options.
If you like it fancy, you could use one of this options:

	-c             Output is colored
	-p             Display charging status
	-t             Display remaining time on current charge
	-w <number>    Define the width of the bar (default: 20, minimum: 3)
	-n             Output a numerical value only (may be useful in your tmux status-bar)

## Conclusion

I wrote Battery for my own needs. It is one of my first Bash-scripts (except
some dozen 3-liners). If it is useful for you, I would be delighted to hear
about that. Feel free to send me an e-mail to
 [marcel.duemmel@aquasign.net](mailto:marcel.duemmel@aquasign.net).

## Contributors

Adam Lazzarato: cleanup of some ugly trailing whitespaces,
                corrections in the readme-file.

