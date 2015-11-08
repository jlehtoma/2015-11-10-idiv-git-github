---
output: pdf_document
---
# Installation instructions

**Workshop:** Version control for more effective collaboration - Introducing Git and 
GitHub.  
**Instructor:** Joona Lehtomäki, University of Helsinki.  
**Place and time:**  German Centre for Integrative Biodiversity Research (iDiv),
2015-11-10.  
**Attribution:** Instructions below adapted from  [Software Carpentry](https://swcarpentry.github.io/git-novice/) released under [CC BY 4.0-license](http://software-carpentry.org/license.html#cc-by).

## Setup

In this workshop, we will be using Git through its command-line interface (CLI) 
meaning that you will need an operational CLI [shell](https://en.wikipedia.org/wiki/Shell_(computing))
such as [Bash](https://en.wikipedia.org/wiki/Bash_(Unix_shell)). The 
instructions for installing the necessary software on Windows, Mac and Linux are 
given below.

[Software Carpentry](http://software-carpentry.org) maintains a list of common 
issues that occur during installation as a reference for instructors that may be 
useful on the [Configuration Problems and Solutions wiki page](https://github.com/swcarpentry/workshop-template/wiki/Configuration-Problems-and-Solutions). In case you run 
into any trouble in installing the software that you cannot solve, please 
contact Joona (<joona.lehtomaki@gmail.com>) in advance.

## The Bash Shell

[Bash](https://www.gnu.org/software/bash/) is a commonly-used shell that gives 
you the power to do simple tasks more quickly. 

#### Windows

Install Git for Windows by downloading and running [the installer](http://msysgit.github.io/). 
This will provide you with both Git and Bash in the Git Bash program.

Run the installer and follow the steps bellow:

1. Click on "Next".
1. Click on "Next".
1. Click on "Next".
1. Click on "Next".
1. Click on "Next".
1. Select **"Use Git from the Windows Command Prompt"** and click on "Next". If you 
forgot to do this programs that you need for the workshop will not work 
properly. If this happens rerun the installer and select the appropriate option.
1. Keep **"Use OpenSSH"** selected and Click on "Next". 
1. Keep **"Checkout Windows-style, commit Unix-style line endings"** selected 
and click on "Next".
1. Select **"Use Windows' default console window"** and click on "Next".
1. Click on "Next".
1. Click on "Finish".

#### Mac OS X

The default shell in all versions of Mac OS X is Bash, so no need to install 
anything. You access Bash from the Terminal (found in 
`/Applications/Utilities`). You may want to keep Terminal in your dock for this
workshop.

#### Linux

The default shell is usually Bash, but if your machine is set up differently you 
can run it by opening a terminal and typing `bash`. There is no need to install 
anything.

## Git

Git is a version control system that lets you track who made changes to what 
when and has options for easily updating a shared or public version of your code 
on e.g. [GitHub](github.com). For GitHub, you will need 
[a supported web browser](https://help.github.com/articles/supported-browsers/) (current versions of Chrome, Firefox or Safari, or Internet Explorer version 9 
or above).

#### Windows

Git should be installed on your computer as part of your Bash install (described 
above).

#### Mac OS X

**For OS X 10.9 and higher**, install Git for Mac by downloading and running the 
most recent "mavericks" installer from 
[this list](http://sourceforge.net/projects/git-osx-installer/files/). After 
installing Git, there will not be anything in your `/Applications` folder, as 
Git is a command line program.  

**For older versions of OS X (10.5-10.8)** use the most recent available 
installer labelled "snow-leopard" 
[available here](http://sourceforge.net/projects/git-osx-installer/files/).

#### Linux

If Git is not already available on your machine you can try to install it via 
your distro's package manager. For Debian/Ubuntu run `sudo apt-get install git` 
and for Fedora run `sudo yum install git`.

## GitHub

Be sure to [register to GitHub](https://github.com/join) before the workshop.

## Text editor

In this workshop, we will be doing simple edits to plain text files, but no 
coding so you will not need features such as syntax highlighting etc. However, 
we will configure Git to use a particular text editor, so choose one of the 
following text editors:

- [Notepad++](http://notepad-plus-plus.org/) (Win)
- [Sublime Text](http://www.sublimetext.com/) (Win/Mac/Linux)
- [Text Wrangler](http://www.barebones.com/products/textwrangler/) (Mac)
- [Gedit](https://wiki.gnome.org/Apps/Gedit) (Linux)
- [Kate](http://kate-editor.org/) (Linux)

You can use whatever text editor you like, but you will have to figure out yourself
how to configure it with Git. **NOTE** On Windows, the use of Notepad is 
strongly discouraged.
