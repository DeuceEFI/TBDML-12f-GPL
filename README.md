# TBDML

Turbo BDM Light interface
(c) 2005, Daniel Malík
rev 1.5


### Introduction

TBDML is a hardware interface which connect between computer and BDM debugging port of Freescale microcontrollers. It enables debuggers and other SW tools to communicate with the microcontroller, download code into its on-chip flash, etc.


### Goals

David Malík developed the TBDML hardware and software to satisfy the following
requirements:

 * low cost
 * ease of assembly and prototyping (widely available through hole components only & simple programming interface for downloading firmware)
 * open-end SW interface with documented API for easy integration into debuggers and new standalone tools
 * easy SW migration under Linux {not quite there yet, these files are for Windows only}
 * support for at least one widely used debugger
 * modern and widely available interface for communicating with the computer (USB)
 * wide range of target MCU supply voltage (at least from 3.3V to 5V)

The SW APIs are based on the Turbo BDM interface David had developed previously. He had developed TBDM interface to achieve maximum accuracy and performance. It was capable of BDM speeds up to 3.75 Mbit/s and timing resolution of 16.7ns. At the same time it was very complicated, expensive, impossible to build without professionally made PCB and the components were hard to get.
I should also mention that the SW is open source. David claimed to certainly not be the best programmer and others should get a chance to make the SW better. He also appreciated that there are situations where somebody might need to do something special and modification of the source code would be needed to achieve it.

 
### Status

This is from materials I have found on the Internet in the public domain and I am posting them here on github.com as a repository for this GPL licensed open source hardware project originally created by David Malík in 2005.

I make no claim to author any part of this software or hardware, I only assembled it in one place for anyone needing a simple to make at home BDM pod that is supported by the Hi-Wave [(c) Freescale] debugger which is part of the CodeWarrior for HCS12(X) Microcontrollers (Classic) [(c) Freescale] which you can download from:

 http://cache.freescale.com/lgfiles/devsuites/HC12/CW_HC12_v5.1_SPECIAL.exe?fpsp=1&WT_TYPE=IDE%20-%20Debug,%20Compile%20and%20Build%20Tools&WT_VENDOR=FREESCALE&WT_FILE_FORMAT=exe&WT_ASSET=Downloads&sr=3

AG 02/12/2012

### Changes

Please contact David Malík with any changes so that he can include them with his original files.

