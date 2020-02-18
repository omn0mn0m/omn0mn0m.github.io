---
title: "How-To: Icestorm Installation in WSL"
date: 2018-01-05T04:36:27-05:00
draft: false
---

As mentioned in my [previous post]({{< relref "calm-before-the-icestorm.md" >}}), I will be spending some time to explore using the open-source [Project Icestorm](http://www.clifford.at/icestorm/) toolchain in the Windows Linux Subsystem (WSL). This is how I was able to set up the tools on my computer, prior to any testing on an actual FPGA board... I am still waiting to purchase one.

These instructions are based on those listed under "Where are the Tools? How to Install?" on the Project Icestorm website. I am writing this blog post as I am installing the tools so that they are as accurate as possible.

EDIT 01-23-19: Replaced Arachne-PNR installation instructions with NextPNR.

## Installing Prerequisites
First, I installed all the Ubuntu prerequisites using the command mentioned in the installation instructions.

```bash
sudo apt-get install build-essential clang cmake bison flex libreadline-dev \
                     gawk tcl-dev libffi-dev git mercurial graphviz   \
                     xdot pkg-config python python3 libftdi-dev \
                     qt5-default python3-dev libboost-all-dev
```

While the command above is noted for Ubuntu 14.04, everythings still works fine with Ubuntu 16.04 (version default with WSL). The command should execute without any errors.

## Installing Icestorm Tools
These tools are the main design tools for Project Icestorm.

The command is copied and pasted from the Project Icestorm website:

```bash
git clone https://github.com/cliffordwolf/icestorm.git icestorm
cd icestorm
make -j$(nproc)
sudo make install
```

This also seems to work without any issues.

## Installing Yosys
This is the synthesis tool for Project Icestorm, and only is compatible with Verilog. The synthesis process converts the hardware-description language (Verilog) into a gate-level netlist. Yosys is meant for Verilog, but there is a VHDL front-end [available](https://github.com/cliffordwolf/yosys-plugins/tree/master/vhdl). I may try to tackle installing it in the future, as I have become more comfortable with VHDL than Verilog.

Like last time, we used the command from the Project Icestorm website:

```bash
git clone https://github.com/cliffordwolf/yosys.git yosys
cd yosys
make -j$(nproc)
sudo make install
```

Once again, there seems to be no issues. Things are looking promising.

## Installing NextPNR
This is the new place-and-route tool for Project Icestorm, replacing Arachne-PNR. In FPGA design, place-and-route describes the process of converting a design into its implementation.


This should be no surprise: Run the command from the Project Icestorm website.

```bash
git clone https://github.com/YosysHQ/nextpnr nextpnr
cd nextpnr
cmake -DARCH=ice40 -DCMAKE_INSTALL_PREFIX=/usr/local .
make -j$(nproc)
sudo make install
```

There are a few dependencies needed to successfully build NextPNR that I was missing. After installing them, everything built correctly. These were included in the pre-requisite command.

## Installing Simulation Tools
For simulations, I used Icarus Verilog. At first, I tried to use Yosys, but came across issues because Yosys only implements the synthesisable language features of Verilog. For viewing the output file, I open the file in GTKWave. 

To install Icarus Verilog, run the following command: `sudo apt-get install iverilog`

To install GTKWave, run the following command: `sudo apt-get install gtkwave`

To run GTKWave, just type `gtkwave` in the shell and import your waveform through the GUI.

## Getting a Template
For now, clone my template project in a directory and run it.

```bash
git clone https://github.com/omn0mn0m/FPGA-Icestorm-Template.git
cd FPGA-Icestorm-Template
make
make sim
```

If everything worked out, the synthesis and place-and-route should have worked without error. You should also be seeing a GTKWave window that you can add waveforms to.

## Conclusion
After installing the Project Icestorm tools, it seems to be a painless and easy-to-do process. Without any sort of FPGA to test with, I am unable to determine if the tools have installed correctly. Hopefully this blog post will help build the confidence of someone who does and happens to be developing in WSL.
