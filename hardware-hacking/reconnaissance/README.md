---
icon: magnifying-glass
---

# Reconnaissance

In this chapter we demonstrate on how to enumerate a device. It makes sense to follow a top down approach and start analyzing from the outside first before opening a device. Opening an unknown device always comes at the risk of triggering a tamper protection or damaging it. Potential weaknesses can be identified without even opening the device.

## Overview

* Closed device
  * OSINT:
    * search the web for public information
    * use FCCID.io to get internal pictures of your device
  * Investigate USB Ports / SD-card
* Opened device
  * Board Analysis:
    * Things to look out for on the PCB:
      * How to identify test pads as potential debug interfaces
      * component identification (flash chips, MCUs, wireless modules)
