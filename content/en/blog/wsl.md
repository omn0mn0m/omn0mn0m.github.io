---
title: "Setting Up My WSL Environment"
date: 2017-10-24T20:44:46-07:00
draft: false
---

Microsoft's Windows Fall Creator Update was the end of Windows Subsystem for Linux (WSL)'s beta phase. As a full feature of Windows, I wanted to integrate it fully into my work environment. The primary objective for this task was to make a functional development environment with little need for leaving WSL. I chose Ubuntu from the Windows Store for my Linux distro.


# Installing X11 Server
One of the first things I did was install an X11 server so I can use GUIs for the programs installed in WSL:

1. Install [vcxsrv](https://sourceforge.net/projects/vcxsrv/)
2. Launch it from the Start menu and leave it running

# Installing Ubuntu
Then, I had to set up WSL and Ubuntu by doing the following:

1. From Windows PowerShell (Admin), I ran `Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux`
2. Restart your computer when it prompts you to restart
2. Download [Ubuntu](https://www.microsoft.com/en-us/store/p/ubuntu/9nblggh4msv6) from Windows Store
3. Run it for the first time. Enter username and password

# Setting Up X11 (for graphics)
As is, Ubuntu will only be able to open programs in the terminal and not as a GUI. To do that, I had to do the following steps:

1. `echo "export DISPLAY=0:0 >> ~./bashrc`

# Setting Up Emacs (optional)
That is all for the basic installation of Ubuntu and WSL. These are additional steps I took to set up my personal development environment. It will install Emacs (with my .emacs.d), Git, GCC, and TexLive.

1. `sudo add-apt-repository ppa:kelleyk/emacs`
2. `sudo apt-get update`
3. `sudo apt-get install git gcc emacs texlive-full`
4. `git clone https://github.com/omn0mn0m/.emacs.d.git --recursive`

# Conclusion
I hope that this blog post will help with getting up and running with your own WSL environment. For a list of Linux packages and their compatibility with WSL, you can check out [this repo](https://github.com/ethanhs/WSL-Programs).

NOTE: I was not able to get a full desktop environment working. When I figure that out, I will post it here.
