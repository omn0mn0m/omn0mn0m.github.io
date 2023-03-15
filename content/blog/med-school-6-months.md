---
title: 'Using FOSS for the First 6 Months of Med School'
date: 2022-02-16T14:25:00.000+00:00
draft: true
tags:
- privacy
- med-school
---

# Introduction
Wow, it has been two years since my last post. A lot of things have happened since then, like a global pandemic that is still going on two years later... Maybe I'll write what I did all pandemic (spoiler alert: not much) one day, but for now, I wanted to write about medical school. I took the MCAT, applied, interviewed, got accepted, and started medical school since my last blog post here. I guess you could say I've been keeping busy.

Over the past two years though, one thing about me hasn't changed at all: I am still committed to using free and open-source software (FOSS) wherever I can. Starting medical school is both exciting and anxiety-inducing at the same time for most students. Of course, I had to make it harder on myself by substituting as many commonly-used tools as possible with FOSS alternatives. Honestly, I barely noticed a difference, and in some cases, it actually simplified aspects of my life compared to my peers.

My goal for this post is to do two things: list some of my everyday tech needs as a medical student and describe what software filled those needs.

# The Student Computing Requirements
As it is the 21st century, technology is a necessary part of education. Medical school is no exception, and right from the first day of acceptance, I was already running into some obstacles to my FOSS-iness from my school's official computing requirements document. I'll be breaking it down point-by-point here reaction-style, with a subsection for anything noteworthy.

> Medical students in the College of Medicine are REQUIRED to have their own personal laptop computer. The information provided on this page should be used as a guide. Use it to determine if the laptop you own today is suitable for your use in medical school or for information to purchase a new laptop.

Okay, easy enough. I still have my laptop from 2017 that runs. Let's see if it meets the "Laptop feature recommendations" they lay out for me.

## Laptop feature requirements
> All personal devices are only permitted to connect to the ATTWIFI campus network

I have long rants about attwifi. Little did I know that 6 months into med school, I would become a champion of the people for making my Zoom profile picture say "Fix the Wifi".

> (PARAPHRASING HERE) Your computer should meet the minimum hardware requirements to be considered a laptop past 2011.

Seriously, I don't think I can find a 32-bit laptop without going to eBay and buying something that was released at latest when I was in middle school. This is a software post, so I'll skip any hardware requirements from now on.

> Windows laptops must run Windows 10. "Pro"-level or higher is recommended.

Okay, good to know even though it won't be relevant, since I use Linux right?

> Linux, UNIX and other similar operating systems are not supported on our network.

Nevermind. I immediately contacted IT. The response boiled down to "we won't stop you, but if you can't connect, we can't help you." I was a concerned, so I decided to bite the bullet and wipe Arch off my laptop. My desktop still has Linux on it, so I was still going to find out how easy it was to connect Linux to the WiFi. Turns out, there were no issues with this. Amazing.

> We recommend that you have a copy of Microsoft Office that contains, at a minimum, Word, Excel and Power Point. For the PC, either Office 2013, 2010 or 2007 is suitable. For the Mac, Office Mac 2011 is suitable. As an alternative, Office 365 is also available to students at no charge. Training classes are available for these software programs.
> 
> Other "office productivity suites" (e.g., Open Office, Google Apps) may be of use, but they are not supported. Your educational material will be provided in Microsoft Word, Power Point or Excel format.

I have not installed Microsoft Office on my own computer(s) since middle school. I have no intentions on starting any time soon. Every lecture has opened just fine in LibreOffice, and I just make sure to export a PDF or .docx file when I turn in assignments. 

Though it's interesting that Google apps are mentioned as unsupported since literally everyone here, including faculty, uses Google Drive. We do in-class collaborative assignments in Google Slides, with each small group taking a slide in a class document. We outline PBL in Google Docs. Google Drive is so widely used, it was specifically unblocked on the College of Medicine WiFi because the lack of Google Drive was causing so much trouble.

+1 FOSS

> Students are expected to run antivirus and antimalware/ antispyware software on their laptop. Free versions of popular programs are available for download (see below).

I'm going to be honest, I have not used an antivirus software in Linux. Viruses are just so rare, and I watch what links I click and what programs I execute. Since my laptop is now Windows, I ended up just using the default Windows Defender with a healthy dose of common sense. Seems fine so far.

> Our email system is Microsoft Outlook. Student access to their email and calendar will be available through the Outlook webmail client. Students are required to read email sent to them through the campus Outlook system.

I like to have my email accessible in two places: my computer and my phone. For emails on my computer, I've honestly just always opened up my inbox in a web browser. Easy FOSS, no troubles there. For my phone, it's a different story. I tried to connect Outlook to the FairEmail app, but no matter what, it just wouldn't authenticate. After talking to IT, the authentication method that FairEmail depends on for Outlook isn't supported by IT and never will be, so I had to download the Outlook mobile app (on my work profile via Shelter).

+1 proprietary software

## Additional information
And now we move onto the additional tech requirements that the school has. Honestly, a lot of it isn't that interesting.

> Duo Security Enrollment is required more information at...

This is for 2FA. I currently use Aegis for my 2FA codes, but my med school requires authentication through Duo Mobile. There was nothing I could do about this, so Duo Mobile app (in work profile) it is.

+1 proprietary software

# Other School-Required Software
Once I got to school, orientation presented me with a new slew of software to try finding FOSS alternatives for. After my crushing defeat from the Student Computing Requirements (1 FOSS : 2 proprietary), I was not ready for this new onslaught.

## Examplify
It's crazy, but I have to take exams in med school. Due to the pandemic as well as ease, all exams must be taken through a software called Examplify. It's your run-of-the-mill invasive spyware force-installed onto your computer by higher education institutions. I tried finding if there is an official Linux version, to no avail. When seeing if it would run on Wine, many online forums said no due to Examplify detecting if it is not run natively on bare-metal. This also meant no VMs. I threw that onto my Windows laptop and called it a day.

+1 proprietary

## Citrix
Many of the hospital records and software I have to access require connection to the hospital/ med school network. Citrix is a very standard solution for remote access. Luckily, they have an official Linux build. Even luckier, it works. Surprisingly, I've had less issues than both my Windows-using and Mac-using classmates with connecting to things through Citrix. While Citrix itself is not FOSS, I consider this a FOSS win that it not only works in Linux, but works more reliably, decreasing my need to use Windows.

+1 FOSS
