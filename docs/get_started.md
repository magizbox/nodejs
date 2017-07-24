# Installation

## Windows

In this section I will show you how to Install Node.js® and NPM on Windows

#### Prerequisites

Node isn’t a program that you simply launch like Word or Photoshop: you won’t find it pinned to the taskbar or in your list of Apps. To use Node you must type command-line instructions, so you need to be comfortable with (or at least know how to start) a command-line tool like the Windows Command Prompt, PowerShell, Cygwin, or the Git shell (which is installed along with Github for Windows).

#### Installation Overview

Installing Node and NPM is pretty straightforward using the installer package available from the Node.js® web site.

#### Installation Steps

**1.** **Download the Windows installer** from the [Nodes.js®](https://nodejs.org/en/) web site.

**2.** **Run the installer** (the .msi file you downloaded in the previous step.)

**3.** **Follow the prompts in the installer** (Accept the license agreement, click the NEXT button a bunch of times and accept the default installation settings).

<center>

![](http://blog.teamtreehouse.com/wp-content/uploads/2015/01/installer.png)

</center>

**4.** **Restart your computer.** You won’t be able to run Node.js® until you restart your computer.

## Ubuntu

In this section I will show you how to Install Node.js® and NPM on Ubuntu

```bash
# update os
sudo apt-get update
# install node with apt-get
sudo apt-get install nodejs
# install npm with apt-get
sudo apt-get install npm
```

# Test

Make sure you have Node and NPM installed by running simple commands to see what version of each is installed and to run a simple test program:

```
> node -v
v6.9.5

> npm -v
3.10.10
```
## Suggested Readings

* [How To Install Node.js on an Ubuntu 14.04 server](https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-an-ubuntu-14-04-server)
* [How to Install Node.js® and NPM on Windows](http://blog.teamtreehouse.com/install-node-js-npm-windows)
