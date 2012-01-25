## What's this
A ruby script to open a new tab (or a new window) and run command in it on Mac OS X.
It is modified based on the answer from tig regarding question posted at [here](http://superuser.com/questions/174576/opening-a-new-terminal-from-the-command-line-and-running-a-command-on-mac-os-x),
I Expanded its feature a bit by allowing -w option top run command in a new window.

## Usage Example:
	./dt ls -l
	will run "ls -l" in a new tab

	./dt -w top
	will run command top in a new window

## Notes
*Tested with Ruby 1.8.7 on Mac OS X 10.7.2
*I have not been able to make the script to run more than one command at once, for example
	./dt "ls -l;top" won't work as expected. I will dig more into this when I know more ruby.


