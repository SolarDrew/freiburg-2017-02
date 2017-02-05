# Freiburg OpenAstronomy Workshop 21st-22nd February 2017

This repository contains the material taught at the OpenAstronomy workshop at Freiburg in February 2017.
The first day is an introduction to Python for scientists already familiar with programming concepts, and the second day covers Astropy and Sunpy.

The introductory Python lessons and the setup instructions below are adapted from the excellent Software Carpentry material.

## Installation and setup

To participate in the workshop, you will need access to the software described below. In addition, you will need an up-to-date web browser.

### Python

Python is a popular language for scientific computing, and great for general-purpose programming as well. Installing all of its scientific packages individually can be a bit difficult, so we recommend Anaconda, an all-in-one installer.

We will teach Python using the Jupyter (IPython) notebook, a programming environment that runs in a web browser. For this to work you will need a reasonably up-to-date browser. The current versions of the Chrome, Safari and Firefox browsers are all supported (some older browsers, including Internet Explorer version 9 and below, are not).

- Windows
    Open http://continuum.io/downloads with your web browser.
    Download the Python 3.5 installer for Windows.
    Install Python 3.5 using all of the defaults for installation except make sure to check Make Anaconda the default Python.
- Mac OS X
    Open http://continuum.io/downloads with your web browser.
    Download the Python 3.5 installer for OS X.
    Install Python 3.5 using all of the defaults for installation.
- Linux
    Open http://continuum.io/downloads with your web browser.
    Download the Python 3.5 installer for Linux.
    Install Python 3.5 using all of the defaults for installation. (Installation requires using the shell. If you aren't comfortable doing the installation yourself stop here and request help at the workshop.)
    Open a terminal window.
    Type

    bash Anaconda-

    and then press tab. The name of the file you just downloaded should appear.
    Press enter. You will follow the text-only prompts. When there is a colon at the bottom of the screen press the down arrow to move down through the text. Type yes and press enter to approve the license. Press enter to approve the default location for the files. Type yes and press enter to prepend Anaconda to your PATH (this makes the Anaconda distribution the default Python).

### SunPy
Given that you have installed Python using Anaconda, we can use the Anaconda environment to install SunPy too.
    To install SunPy launch a system command prompt or the 'Anaconda Command Prompt' (under Windows).
    Configure conda for sunpy downloads:

     `conda config --add channels conda-forge --add channels astropy`

    Then to install SunPy

     `conda install sunpy astroquery `

Once you are done installing the software listed above, please go to this page, which has instructions on how to test that everything was installed correctly.
