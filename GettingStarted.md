# punch-time-tracking: Installation and Getting Started #

## Prerequisites ##

### todo.txt ###

punch-time-tracking works alongside the todo.txt task management program. Installation instructions can be found [here](http://ginatrapani.github.com/todo.txt-cli/).

### Python ###

punch-time-tracking requires the Python programming language to be installed on your computer. The easiest way to determine if you have Python installed on your system is to run this command at your command prompt:

python --version

This should return a short description of the Python version you are running.

Apple Mac OS X versions later than 10.2, as well as most Linux distributions will have Python pre-installed. For Cygwin users, the Python package will be installed if you use the default package list. If you are using a custom package list, select the 'python' package under the 'Python' category for a minimal installation that will work with punch-time-tracking.

## Installation ##

Download the latest Zip archive from this web site. The zip archive will contain two files. Punch.py is the punch-time-tracking executable file, and should be extracted to a location of your choosing (the same directory where todo.sh has been installed is recommended).

After this has been done, edit your .bash\_profile file to create an alias for punch.

For example,

alias punch="python ~/Punch.py"

could be used if Punch.py was extracted to your home directory.

One this has been done, restart your console or command prompt session to allow the alias to take effect.

## Using punch-time-tracking ##

To review the available commands and options for punch-time-tracking, simply type 'punch' at the command line. This will provide the latest information for the version of punch-time-tracking that you have installed.