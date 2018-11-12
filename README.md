# makescript
Makescript is a set of scripts to make and manage scripts on your Linux system.
The scripts will default to making and editing scripts in $HOME/bin, and will keep previous versions in $HOME/bin/bak

Files (preview):
* makescript -- Creates a news script using provided options, and launches an editor.
* editscript -- Makes a copy of a previously created script, increases the version number of the script, sets the last edited date in the script, and launches an editor.
* importscript -- Imports a script into a makescript framework.
* msinstall -- Installs the scripts onto the system. Note that if the suite is installed onto the system, only root can edit the provided script files. Installing the scripts onto the system requires root or sudo access.
            
All provided scripts have a --help and a --version option, and all scripts created using makescript have a --version option.

Option iteratation section shamelessly lifted from https://natelandau.com/boilerplate-shell-script-template/
