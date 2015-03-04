# dm3 to mrc converter

A shell script for batch converting .dm3 micrographs to .mrc format from the nautilus/nemo context menu.
DM3 files are a common format for digital micrograph files. MRC is a file format used in several electron microscopy reconstruction packages such as Relion. This script simply calls the proc2d program from the <a href="http://blake.bcm.edu/emanwiki/EMAN/">EMAN1</a> reconstruction package. It can be easily modified, and is intended to save time when working with a large number of files.

####For Nautilus (Ubuntu):
Place apropriate file under:&nbsp;&nbsp;&nbsp; /home/$USER/.local/share/nautilus/scripts

####For Nemo (Linux Mint):
Place apropriate file under:&nbsp;&nbsp;&nbsp; /home/$USER/.gnome2/nemo-scripts

An example of the script's usage:

<img src="http://i.imgur.com/J5XCDF1.png" title="nemo_context_menu_screenshot.png" /></a>

There is also a script (command-line-converter) for converting directly from the terminal. If using this script, I suggest adding an alias for it in bashrc.
