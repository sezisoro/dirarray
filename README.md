# dirarray
A bash script to have a directory history similar to the dirstack in ZSH.
###Description
The command to use this feature is ```cds```. In most cases, you can use it just as ```cd``` and you can alias it to ```cd``` in your shell. Where this program shines is every time you cd to a directory, a file (loc: ```~/.cache/dirs```) is updated with the last location moved to, and you can view this as a list with ```cds -``` or navigate to one of the listed options with ```cds -n``` where n is a number within list bounds.
###Installation
Just save the ```.bash_dirarray``` file in your home directory and source it from your ```.bashrc``` or ```.bash_login``` file (add the line ```source ~/.bash_dirarray``` somewhere in one of those files) and after your next login (or after you source the file manually) a file holding the array will be created if nonexistent and any time you use ```cds``` it will be updated.
###Notes
This script is intended only for bash users. ZSH already has a builtin feature from which this was inspired, and other modern shells probably also have similar capability.
