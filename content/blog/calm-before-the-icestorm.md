---
title: "Calm Before The Icestorm"
date: 2017-12-12T03:29:14-05:00
draft: false
---

I have a deep love for field-programmable gate arrays (FPGA). They are both versatile and efficient when designed correctly, and we are able to do most things a microcontroller can but faster. This is achieved by designing a logic circuit that is implemented on the FPGA, rather than running sequential instructions like with a microprocessor on a microcontroller. This allows for better parallelised implementations.

That being said, they are not exactly the most friendly in terms of skills needed or the availability of tools. Xilinx, one of the largest FPGA manufacturers, has some amazing tools available for making digital designs for their chips. They just also happen to be behind a paywall if you're using anything other than their most common consumer chips.

<center>
{{< figure src="/img/posts/icestick-lattice.png" title="The Lattice ICEstick, a $25 FPGA" >}}
</center>

There is one project out there, [Project Icestorm](http://www.clifford.at/icestorm/), that attempts to reverse-engineer and provide "a fully open source Verilog-to-Bitstream flow". This project targets Lattice Semiconductor's iCE40 FPGAs. As a supporter of free and open-source software, I am all for this.

<center>
{{< figure src="/img/posts/upduino-lattice.png#center" title="The Gnarly Grey UPDuino, an $8 FPGA" >}}
</center>

Over the next few months, I will be purchasing an FPGA development board with a Lattice iCE40 (they are actually rather cheap) and trying to write a few useful applications for it. The two boards I am considering are the [iCEstick](http://www.latticesemi.com/icestick) and the [UPDuino](http://www.latticesemi.com/en/Products/DevelopmentBoardsAndKits/GnarlyGreyUPDuinoBoard.aspx). Most importantly, I will be trying to use Project Icestorm for my FPGA toolchain and getting it to run in WSL. As I progress, I will be uploading tutorials and spotlights of my projects.