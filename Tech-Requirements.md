#Setup

Once you've installed all of the software below, test your installation by following the instructions at the bottom on this page.

## 1. The Bash Shell
Bash is a commonly-used shell that gives you the power to do simple tasks more quickly.

#### Windows

Install Git for Windows by downloading and running the [installer](http://msysgit.github.io/). This will provide you with both Git and Bash in the Git Bash program. **NOTE**: on the ~6th step of installation, you will need to select the option "Use Windows' default console window" rather than the default of "Use MinTTY" in order for nano to work correctly.

After the installer does its thing, it leaves the window open, so that you can play with the "Git Bash".

Chances are that you want to have an easy way to restart that Git Bash. You can install shortcuts in the start menu, on the desktop or in the QuickStart bar by calling the script /share/msysGit/add-shortcut.tcl (call it without parameters to see a short help text).

#### Mac OS X

The default shell in all versions of Mac OS X is bash, so no need to install anything. You access bash from the Terminal (found in `/Applications/Utilities`). You may want to keep Terminal in your dock for this class.

#### Linux

The default shell is usually Bash, but if your machine is set up differently you can run it by opening a terminal and typing bash. There is no need to install anything.

## 2. Google Chrome & Firefox

We'll be using Google Chrome as out main web browser. Download [here](https://www.google.com/chrome/). 

For Selenium, we need to use Firefox. Download [here](https://www.mozilla.org/en-US/firefox/new/).

## 3. Python
Python is a popular language for scientific computing, and great for general-purpose programming as well. Installing all of its scientific packages individually can be a bit difficult, so we recommend an all-in-one installer.

Regardless of how you choose to install it, please make sure you install Python version 3.2 or above.

For helpful information on switching between Python 2 and 3 environments in Anaconda, see [here](https://www.continuum.io/blog/developer-blog/python-3-support-anaconda).

We will teach using the Jupiter (aka IPython) notebook, a programming environment that runs in a web browser. Jupiter notebooks are included in the all-in-one installer.

####Windows

* Download and install [Anaconda](https://store.continuum.io/cshop/anaconda/).
* Download the default Python 3 installer. Use all of the defaults for installation except make sure to check **Make Anaconda the default Python.**

####Mac OS X

* Download and install [Anaconda](https://store.continuum.io/cshop/anaconda/).
* Download the default Python 3 installer. Use all of the defaults for installation except make sure to check **Make Anaconda the default Python.**

####Linux

We recommend the all-in-one scientific Python installer [Anaconda](http://continuum.io/downloads.html). (Installation requires using the shell and if you aren't comfortable doing the installation yourself just download the installer and we'll help you during the class.)

1. Download the installer that matches your operating system and save it in your home folder. Download the default Python 3 installer.
2. Open a terminal window.
3. Type `bash Anaconda-` and then press tab. The name of the file you just downloaded should appear.
4. Press enter. You will follow the text-only prompts. When there is a colon at the bottom of the screen press the down arrow to move down through the text. Type `yes` and press enter to approve the license. Press enter to approve the default location for the files. Type `yes` and press enter to prepend Anaconda to your `PATH` (this makes the Anaconda distribution the default Python).

##Testing your installation

Open a command line window ('terminal' or, on windows, 'git bash'), and enter the following commands (without the $ sign): 

```bash
$ python --version
```

The python version should include "Anaconda" and its version information.

Jupyter notesbook is a python development environment that comes pre-installed with the Anaconda python distribution. To see if you have it, type the following into your terminal window:

```bash
$ jupyter notebook
```

This should open a programming interface in your default web browser. It may take a few minutes the first time. To close, just close your browser and then `CTRL-C` to end the process in the command line.

Software Carpentry maintains a list of common issues that occur during installation may be useful for our class here: [Configuration Problems and Solutions wiki page.](https://github.com/swcarpentry/workshop-template/wiki/Configuration-Problems-and-Solutions)

Credit: Thanks to [Software Carpentry](http://software-carpentry.org/workshops/) for providing installation guidelines.
