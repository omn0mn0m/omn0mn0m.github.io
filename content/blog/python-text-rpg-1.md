---
title: "[Python Text RPG 1] Making the Python Boilerplate"
date: 2018-08-28T16:45:46-04:00
categories: [ "python", "tutorial" ]
draft: false
---
Continuing from the previous tutorial, we'll now be filling out skeleton files and getting ready to start writing code.

## Writing Files
For the sake of time, we are going to copy-and-paste a lot in this tutorial. A short explanation of what is going on in each file will also be included.

### setup.py
```python
# -*- coding: utf-8 -*-

from setuptools import setup, find_packages


with open('README') as f:
    readme = f.read()

with open('LICENSE') as f:
    license = f.read()

setup(
    name='dungeoncrawler2',
    version='0.1.0',
    description='A text-based RPG written in Python 3',
    long_description=readme,
    author='Nam Tran',
    author_email='tranngocnam97@gmail.com',
    url='https://github.com/omn0mn0m/Dungeon-Crawler-2',
    license=license,
    packages=find_packages(exclude=('tests', 'docs'))
)
```

### Makefile
```
init:
	pip3 install -r requirements.txt

test:
	python3 -m pytest --cov=dungeoncrawler2

.PHONY: init test
```

Now would be a good time to note that I use pip3 and python3 in my Makefile. If you only have Python 3 installed, you can use pip and python, respectively.

## Setting Up virtualenv
virtualenv is a Python package for creating isolated development environments for each Python project you are working on. To use it, first you have to install it: `pip3 install virtualenv`

Now within your project root directory, type `virtualenv -p /usr/bin/python3.6 venv`

From now on, any time you want to program you need to first run `source venv/bin/activate` in your project root. When you are done with the virtual environment, run `deactivate`

## Conclusion
What we have completed is created most of the environment necessary for starting to write our code. You should be good to commit and push everything to GitHub.

If you have been paying close attention, you should have noticed we haven't done anything to the docs directory. That's for a later tutorial. For now, we just set up the files necessary to start coding. In next tutorial, we'll start writing some Python!