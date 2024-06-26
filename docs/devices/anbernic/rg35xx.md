# Anbernic RG35XX (Original)

![](../../_inc/images/devices/anbernic-rg35xx.png){ .off-glb }

## Overview

| Device | CPU / Architecture | Kernel | GL driver | Interface |
| -- | -- | -- | -- | -- |
| RG35xx Original | Actions Semi 7039 (ARM) | Actions Semi BSP 4.9.170 | pvrsrvkm | Emulation Station / Simplemenu |

!!! warning "The RG35XX distribution includes a bootloader, u-boot, and kernel in binary form extracted from the stock firmware. There are no public sources provided by anbernic for those"

## Extracting the kernel and bootloader

Anbernic has not published the source code of the u-boot and kernel of the RG35xx (original). In order to have a working configuration you have two options:

* You can use the stock kernel, bootloader, and u-boot from the stock SDCARD. See below for instructions on how to extract those. 
* You can compile the included kernel with the source code of this distribution, however, note that there will be a few elements that are missing

The firwmare included in releases uses the kernel, bootloader, and u-boot from the stock firmware.

## Features

* Suspend (briefly press power button)
* HDMI
* Dual frontend: choose between Emulation Station or Simplemenu
* Wireless support with compatible USB-Wifi dongles

## Notes

### Installation

Download the latest `RG35XX` version of KNULLI from the button below and follow the instructions listed on the [Install](../../../play/install/) page.





