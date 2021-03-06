---
title: "[Python Text RPG 0] Setting Up Shop"
date: 2018-08-27T16:45:46-04:00
categories: [ "python", "tutorial" ]
draft: false
---
When I first taught myself how to program, the first project suggested to me was to make a text-based RPG from scratch (no third-party libraries). At the time, I was learning Java so I could program my school's FRC robot so naturally the RPG was written in Java. The goal of this blog mini-series is to make yet another text-based RPG, but now in Python. For this tutorial series, I'll be saying what to do, then show what I typed at the end if I think you can figure it out.

## Command Line: A Primer
For this tutorial series, we will be using the command line for as many things as possible. This is because it is can be a difficult skill for many, while using a GUI is not and relatively intuitive. With that in mind, here is a VERY brief intro to using the command line. For now, it will be for Linux (I'll write Mac and Windows instructions later when I'm not as lazy).

### Opening the Command Line
This can vary based on what Linux distro you're using. For Ubuntu, you can use the shortcut `Ctrl-Alt-t`.

### Basic Operations
Here are some commands to get you started:

- `cd type/a/directory/here`: Changes directory to the one you specify
- `ls`: Prints the contents of your current directory
- `mkdir`: Makes a directory
- `touch file-to.create`: Creates an empty file
- `rm file-to.delete`: Deletes the file you specify. You can delete entire folders like: `rm -r type/a/directory/here`.

## Installing Some Software
You need to install the following software for this tutorial series to get started. We'll add more software as it all becomes relevant.

- Git: `sudo apt-get install git`
- Make: `sudo apt-get install build-essential`
- Pip: `sudo apt-get install python3-pip`

Most Linux distros come with Python already installed.

## Setting Up GitHub
The first step to take (and one I didn't know back then) is to set up version control for your project. So [create a GitHub account](https://github.com/signup) and make a [new repository](https://github.com/new). I'm naming the repo "Dungeon-Crawler-2". Leave it public since that's free.

Feel free to initialise the repo with a README, .gitignore, and LICENSE. I am choosing "Python" for the .gitignore and "GNU General Public License v3.0" for the license.

Next, you'll want to clone your repository. This just means downloading a local copy that you can upload back to GitHub with your new changes later. Because we aren't scrubs, we'll be downloading the [command-line tool](https://git-scm.com/downloads).

Once it is installed, type the following `git clone https://github.com/<TYPE YOUR USErNAME HERE>/<TYPE YOUR REPO NAME HERE>.git`

Don't copy and paste the above command, type it out and fill in the areas where it tells you to type stuff.

You should now have a directory on your computer named the same as your GitHub repo name.

## Setting Up An Incomplete Project Skeleton
First, change your directory to your git repo you just made. The following is an adaptation of [this structure guide](https://docs.python-guide.org/writing/structure/#further-reading).

Next, you need to make the following directories:
- docs
- dungeoncrawler2
- tests

Now make the following files:
- setup.py
- requirements.txt
- Makefile
- dungeoncrawler2/__init__.py
- dungeoncrawler2/dungeoncrawler2.py
- docs/conf.py
- docs/index.rst
- tests/test_dungeoncrawler2.py

Add every new file for tracking with `git add --all`.

Then make a commit for the series of changes you made with `git commit -am "Initial commit"`.

Finally, push your changes with `git push`.

That's it for this first tutorial. Next tutorial, we'll be filling in the files in our project skeleton and setting up our development environment!

### Cheats
- Changing directory to your git repo: `cd <TYPE YOUR REPO NAME HERE>`
- Making the directories (just the first one, you should be able to figure it out from there: `mkdir docs`