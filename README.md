# Freiburg OpenAstronomy Workshop 21st-22nd February 2017

This repository contains the material taught at the OpenAstronomy workshop at Freiburg in February 2017.
The first day is an introduction to Python for scientists already familiar with programming concepts, and the second day covers Astropy and SunPy.

The introductory Python lessons and the [setup instructions below](#installation-and-setup) are adapted from the excellent [Software Carpentry](https://software-carpentry.org/lessons/
) material.

If you have any questions about this workshop or its contents, or if you would like to arrange a similar workshop, feel free to contact [Stuart Mumford](mailto:stuart.mumford@aperiosoftware.com) or [Drew Leonard](mailto:andrew.leonard@aperiosoftware.com).

## Schedule

| | **Day 1** | **Day 2** |
| :---: | :---: | :---: |
| 09:00 | Introduction and software setup | -- |
| 09:30 | [Version Control with Git](http://swcarpentry.github.io/git-novice/) | [Intro to SunPy]() |
| 10:50 | Coffee | Coffee |
| 11:10 | [An Introduction to Python](./02-Python-Intro/index.ipynb) | [Images in Solar Astronomy]() |
| 12:30 | Lunch break | Lunch break |
| 13:30 | [Units and Plotting](./03-multid-images/images-and-plotting.ipynb) | [Obtaining and Coaligning Data]() |
| 14:50 | Coffee | Coffee |
| 15:10 | Exercise: [Approximating Pi](./04-Animation/04-Animation-Excercise.ipynb) (end 16:30) | Exercise: [Inspecting Spectral Data]() (end 16:00) |

## Installation and setup

To participate in the workshop, you will need access to the software described below. In addition, you will need an up-to-date web browser.

### Git

Git is a version control system that lets you track who made changes to what when and has options for easily updating a shared or public version of your code on github.com. You will need a supported web browser (current versions of Chrome, Firefox or Safari, or Internet Explorer version 9 or above).

#### Windows

Download the Git for Windows installer. Run the installer and follow the steps below:

1. Click on "Next".
1. Click on "Next".
1. Click on "Next".
1. Click on "Next".
1. Click on "Next".
1. Select "Use Git from the Windows Command Prompt" and click on "Next". If you forgot to do this programs that you need for the workshop will not work properly. If this happens rerun the installer and select the appropriate option.
1. Click on "Next". Keep "Checkout Windows-style, commit Unix-style line endings" selected.
1. Select "Use Windows' default console window" and click on "Next".
1. Click on "Next".
1. Click on "Finish".

This will provide you with both Git and Bash in the Git Bash program.

#### Mac OS X

For OS X 10.9 and higher, install Git for Mac by downloading and running the most recent "mavericks" installer from [this list](http://sourceforge.net/projects/git-osx-installer/files/). After installing Git, there will not be anything in your /Applications folder, as Git is a command line program. For older versions of OS X (10.5-10.8) use the most recent available installer labelled "snow-leopard" [available here](http://sourceforge.net/projects/git-osx-installer/files/).

#### Linux

If Git is not already available on your machine you can try to install it via your distro's package manager. For Debian/Ubuntu run sudo apt-get install git and for Fedora run sudo yum install git.

### Python

Python is a popular language for scientific computing, and great for general-purpose programming as well. Installing all of its scientific packages individually can be a bit difficult, so we recommend Anaconda, an all-in-one installer.

We will teach Python using the Jupyter (IPython) notebook, a programming environment that runs in a web browser. For this to work you will need a reasonably up-to-date browser. The current versions of the Chrome, Safari and Firefox browsers are all supported (some older browsers, including Internet Explorer version 9 and below, are not).

#### Windows
1. Open http://continuum.io/downloads with your web browser.
1. Download the Python 3.5 installer for Windows.
1. Install Python 3.5 using all of the defaults for installation except make sure to check Make Anaconda the default Python.

#### Mac OS X
1. Open http://continuum.io/downloads with your web browser.
1. Download the Python 3.5 installer for OS X.
1. Install Python 3.5 using all of the defaults for installation.

#### Linux
1. Open http://continuum.io/downloads with your web browser.
1. Download the Python 3.5 installer for Linux.
1. Install Python 3.5 using all of the defaults for installation. (Installation requires using the shell. If you aren't comfortable doing the installation yourself stop here and request help at the workshop.)
1. Open a terminal window.
1. Type ```bash Anaconda``` and then press tab. The name of the file you just downloaded should appear.
1. Press enter. You will follow the text-only prompts. When there is a colon at the bottom of the screen press the down arrow to move down through the text. Type yes and press enter to approve the license. Press enter to approve the default location for the files. Type yes and press enter to prepend Anaconda to your PATH (this makes the Anaconda distribution the default Python).

### SunPy
Given that you have installed Python using Anaconda, we can use the Anaconda environment to install SunPy too.

1. To install SunPy launch a system command prompt or the 'Anaconda Command Prompt' (under Windows).
1. Configure conda for sunpy downloads:

```conda config --add channels conda-forge --add channels astropy```

Then to install SunPy

```conda install sunpy astroquery```
