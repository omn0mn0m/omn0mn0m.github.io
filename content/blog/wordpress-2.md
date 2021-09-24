---
title: "WordPress: Hello Java, My Old Friend"
date: 2016-09-21T08:25:46-07:00
draft: false
---
*EDIT: This blog post comes unedited from my (now nonexistent) Wordpress blog. Pictures have not been included, however.*

Today, I wrote a basic "Hello World" program in Java (almost 3 years since the first time). I am using Bash on Ubuntu on Windows, Command Prompt, and Powershell for all my programming needs. While that does not seem difficult, it took me almost one hour from start to finish. The first of my issues began when I could not remember how to save in Emacs. After a quick Google search, I figured out that it was just C-x C-s. Then I had to figure out how to quit Emacs. At this point, I gave up and just exited the terminal.

The second issue came after the program was written. I was pleasantly surprised while I was coding that Emacs had syntax highlighting for Java. Afterwards though, there was only disappointment. After saving and exiting, I attempted to compile in Command Prompt using javac. Command Prompt could not find javac. I edited the Path variable to point to my Java SDK installation. It compiled and I thought I was in the clear. I was not.

I tried to run the program using java HelloWorld. It had an error. I went back to my Path variable and tried to delete a path that led to an Oracle folder, as suggested on Stack Overflow. Nothing. I tried to point to the JRE. Still nothing. Eventually I found out that the 64-bit JRE does not come with everything required to run a Java programme and must be installed alongside a 32-bit JRE. After doing that, everything ran and I finally got the "Hello World!" I was desperately hoping to see. I had never had an issue like this before in Eclipse.

What seemed like a simple task for me as I have written much more difficult programmes in the past turned out to be an ordeal that took up a good chunk of my day after I was done with classes...