# Basics

## Information

[Official website](https://vim.sourceforge.io/)

[Repository](https://github.com/vim/vim)

## Installing vim

*Vim is available by default in most UNIX distributions, but if you got rid of it at some point, here is how to get it back up and running:*

### Debian

    sudo apt-get install vim

### Mac



### Windows

With bash on Ubuntu :

    sudo apt-get install vim

In cmd:

    Download and install from http://www.vim.org/download.php/#pc and add to path

## Using vim

### Vim modes

While using vim, you'll mainly encounter 3 modes:

* Waiting for a command
    * This is the default mode
    * Can be reached from both others by pressing 'esc'
    * Allows the user to move in the text via the arrow keys
* edit
    * Recognisable by the fact that '-- INSERTION --' is written at the bottom of the command line
    * Allows the user to type in the text as in any other editor
    * Get in this mode by pressing 'i'
    * Get out of this mode by pressing 'esc'
* Command input
    * Reached by typing ':' from the waiting mode
    * Allows the user to save changes, exit the editor, ...
    * Get out of this mode by pressing 'esc'

