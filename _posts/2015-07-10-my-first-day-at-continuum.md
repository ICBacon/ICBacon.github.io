---
layout: post
title: Installing Miniconda3 for a Mac OS X
---

**{{ page.title }}** written in markdown.

**The purpose of this post is to demonstrate the process of how to install Miniconda3 for a Mac OS X operating system  by using Markdown formatting.**

* *Download the Miniconda File to Install*

  * To begin, click on the link below which will direct you to the Miniconda installation packages.
  
    * [Miniconda Installer](http://conda.pydata.org/miniconda.html)
  * Once there, download the 64-bit (bash installer) for Python 3.4 in the Mac OS X section.
  * There may be a warning that could pop up about the file downloaded being a potential hazard for the computer and will prompt you to either continue or cancel the file. If you do not have this pop up, then disregard this step and continue.
  * In opening the file that was just downloaded, it will be opened in a text editor since it is written as a shell script file.

- *The Terminal*

  - Open a new command line in the terminal
  - After doing so, type *ls* to see the current directory. It should already be in the main directory when opened for the first time
  - Since the file was downloaded, it'll be located in the downloads folder from the main directory.
  - Type *cd Downloads* to go into that directory.
  - To run a non-executable .sh-script in the terminal, type *sh myscript*
    
    - [How to run a .sh-script in a Mac terminal](http://stackoverflow.com/questions/733824/how-to-run-a-sh-script-in-an-unix-console-mac-terminal)
  - The user will then be prompted "In order to continue the installation process, please review the license agreement. Please, press ENTER to continue". After reading, press Enter.
  - The user will then be prompted "Do you approve the license terms? [yes|no]". Type yes to proceed with installation or no to end.
  - Finally, the user will be prompted twice to confirm the location of where Miniconda3 will be installed or if the user has a different preference for the location.

* *Congrats! Miniconda3 has now been installed on the Mac OS X system!*
