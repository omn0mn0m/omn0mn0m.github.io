+++
date = 2020-02-14T09:00:00Z
draft = false
tags = ["privacy"]
title = "Breaking the Chains #5 - Switching to Free and Open-Source Software"

+++
For anyone who has been following this series until now, the changes to my digital habits that I've mentioned have been relatively small. Signal behaves just like a normal texting app, and Firefox is just another web browser. For a complete discussion about how I have and will continue working on protecting my digital rights, I'm going to have to eventually talk about how I switched from using Windows to Linux as my primary operating system. Switching operating systems isn't an easy task by any means.

Rather than dive off the deep end right away and go through steps for that, I'm gonna write a few posts detailing some common free and open-source software (FOSS) I had to get used to using when I switched over. Almost all the popular FOSS alternatives are available on Windows as well, so by switching to them early, the transition to Linux will be less painful. It's also ["I Love Free Software" Day](https://fsfe.org/campaigns/ilovefs/), so why not make the switch and get in the holiday spirit?

# What is Linux?

Let me back-track a bit first, since I don't think I ever explained what Linux is. It is a free and open-source operating system  based on UNIX, meaning it shares a common ancestor with macOS. One great thing about Linux is that because it is open-source, there are hundreds of versions of Linux out there, called distributions or distros. Whether you're [[used to macOS](https://itsfoss.com/macos-like-linux-distros/) or [used to Windows](https://www.fossmint.com/linux-distribution-for-windows-users/), you can find a distro that tries to be user-friendly for you.

Free means free as in "free speech", not free as in "free beer", by the way. That means you can do whatever you want with Linux after you install it. There's no constant "Activate Windows Now" watermark if you're using the free version. You're not relying on a company to hopefully continue supporting your favourite OS.

I'll be doing a whole series of posts describing my switch to Linux in the future, so stay tuned. Changing your operating system is definitely an important step in taking control of your technology and privacy, so my blog would be incomplete without a few posts about switching.

# Why Free and Open-Source Software?

I'm not going to go into details as to why you should use free and open-source software, especially when there are [so many](https://en.wikibooks.org/wiki/FOSS_A_General_Introduction/Why_FOSS%3F) resources out there that [list the reasons](https://www.pcworld.com/article/209891/10_reasons_open_source_is_good_for_business.html).

All I'm going to say is that we, as citizens of a technological global society, should have the freedom over our software in the same way that we should have freedom of speech or freedom to vote. While most free and open-source software is free of charge, that isn't necessarily always true. What is true is that once I buy it, I am able to redistribute it and modify it as I please. If I'm able to resell my old textbooks, why shouldn't I be able to sell a copy of Adobe Photoshop I don't use anymore?

Anyways, I'll get off my soapbox now, and start listing some free and open-source software that you should be switching to that I have been using for years now with very few issues.

# List of Software

## 1. Microsoft Office => LibreOffice

Oh Microsoft Office, you're the reason I started using FOSS. Back in middle school, my family bought a new family desktop. One issue was that it didn't come with Microsoft Office, so I wasn't able to complete my schoolwork. I ended up finding LibreOffice after searching on Google. It comes with everything you'd want from Microsoft Office. While the default file types for LibreOffice are OpenDocument formats, it does come with compatibility for all your Microsoft formats (docx, pptx, xlsx, etc).

Since this is a privacy blog series, I have to mention that Microsoft Office has some serious privacy issues to it. It collects user data like its no one's business. The issue is so bad that Microsoft Office is [banned in some German schools](https://www.zdnet.com/article/microsoft-office-365-banned-in-german-schools-over-privacy-fears/). That's not the only time that a European country has had issues with Microsoft Office though. The Dutch government reported in 2018 that [Microsoft Office's telemetry violates the GDPR](https://www.zdnet.com/article/dutch-government-report-says-microsoft-office-telemetry-collection-breaks-gdpr/). The switch to LibreOffice isn't really all that hard, and it definitely is worth it for the money saved or at the very least for the privacy gained.

Download LibreOffice [here](https://www.libreoffice.org/). I recommend the latest version, not the stable version.

## 2. Mail => Thunderbird

If you don't like opening your emails in your web browser, or want to get notifications more easily on your desktop when new emails arrive, you're probably using an email client already. For a long time, I used the default Mail app that came with Windows 10. When I switched to Linux, I missed it a lot since I don't check my phone often when I'm on my computer. 

This led me to finding and installing Thunderbird for all my communications needs. I said all my communication needs because it really does handle most of my communications needs. I use it to keep up with my RSS blog feeds, sync my email inbox, and connect to IRC channels. It does all of these things well, and while it does not get official support from Mozilla anymore, the dev community is still alive and well.

Once again, we have to mention privacy as well. Microsoft really likes to mess with our privacy (really every tech company does these days). Bck in 2018, Microsoft [tried to show personalised ads](https://www.forbes.com/sites/jasonevangelho/2018/11/16/microsoft-wants-to-show-you-ads-in-the-windows-10-mail-app) on their mail app. I definitely want both Microsoft and my email provider (Google) spying on my stuff just to give me some ads they think I want to see. So once again, switch for the convenience of Thunderbird or the privacy of not having Microsoft snooping your inboxes. Either reason is valid.

Download Thunderbird [here](https://www.thunderbird.net/en-US/).

## 3. Groove Music/ Microsoft Movies & TV => VLC Media Player

Here's a 2-for-1 deal for you. VLC Media Player can be used to both listen to music files and watch videos. This makes it a great choice to replace the default software installed on Windows for these purposes. It's a versatile program that does so much more than just play media files, by the way. VLC also lets you subscribe to podcasts, transcode your files from one format to another, and record your desktop. Another cool thing is that it also is released as a mobile app, so you can use it on your phone as well, if you so choose.

Surprisingly, I don't have any privacy complaints about Groove Music or Microsoft Movies & TV. Huh. I would still recommend switching simply because of how powerful VLC is and also because you'll most likely have to use it if you switch to Linux.

Download VLC Media Player [here](https://www.videolan.org/vlc/).

## 4. Adobe Reader => Firefox (For Now)

Firefox, and other modern web browsers, come with a built-in PDF reader. Most flavours of Linux come with their own dedicated PDF reader, but since you'll most likely still be using Windows or Mac OS after this post (for now), Firefox will be the next closest available software.

Now, you may be asking what's wrong with Adobe Reader. Firstly, it is proprietary software. Secondly, it has a lot of major security flaws. One such security flaws is in the nature of how PDF forms work, so that feature will be missing in most open-source PDF readers. You'll get used it, I promise. Adobe has been [fixing these vulnerabilities lately](https://www.zdnet.com/article/adobe-addresses-over-40-vulnerabilities-many-critical-in-patch-update/), but I have no reason to wait around for them.

Download Firefox [here](https://www.mozilla.org/en-US/firefox/new/). You can also read [my post about Firefox](https://omn0mn0m.github.io/blog/breaking-the-chains-2/) about making Firefox your main browser.

# Conclusion

As I've previously mentioned, I've been using the software on this list for years. Almost all of college, I have been using all the software mentioned above, and there were very few times that it ever caused me any headache. The switch isn't that bad, you just have to be in the right mindset to do it. Free and open-source software is often worked on by volunteers, so sometimes there are bugs. Just keep a cool head, search on forums for a solution, and remember that there are thousands (sometimes millions) of other users. Your software being open-source means that someone motivated enough will have probably already written a fix. Proprietary software [aren't bulletproof either](https://www.ghacks.net/2019/05/08/microsoft-releases-buggy-office-2016-patch-kb4462238-a-day-after-release/), but at least this time the software was free.
