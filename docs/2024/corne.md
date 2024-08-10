---
layout: default
title: Corne
parent: 2024
nav_order: 1
---

# Corne

I've been using a Preonic layout (5x12 ortholinear layout) for the past 2~3 years and it has been an amazing transition from a regular keyboard. But lately, my back, shoulders, and wrists have been killing me. So this time around, I'll be building a wireless Corne - a 42 key split keyboard.

## The PCB

### Available options

From my previous handwired builds, I learned that handwiring is very time consuming. I knew I wanted to use a PCB this time around - possibly even have it made by a vendor like JLCPCB. There were a lot of variants of Corne that each had different characteristics. I have previously used a 5 column split keyboard like the [Charybdis Nano](https://github.com/Bastardkb/Charybdis) (3x5+3) and I learned I needed a 6th column for `ESC`, `TAB`, `SHIFT`, and `ENTER`.

{: .note }

> [Catalog of Corne Variants](https://www.reddit.com/r/crkbd/comments/11i0tb4/comment/jb07n1q/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button) by [/u/skrobul](https://www.reddit.com/user/skrobul/)

### The decision

I decided I would use the [cho-corne-ice](https://github.com/e3b0c442/crkbd/tree/cho-corne-ice) by [e3b0c442](https://github.com/e3b0c442). It had a sleek design with the reset button on the side and a small power switch below that would situate below the USB-C port. The build guide and required parts were very well documented to be easily reproducible. All the parts were also readily available on Aliexpress.

### Hotswap sockets

![PCB Before Solder Switch]({{site.baseurl}}/images/2024/corne/pcb_before_switch.jpg)
![PCB After Solder Switch]({{site.baseurl}}/images/2024/corne/pcb_after_switch.jpg)

### MCU, Reset switch, Power switch, Battery connector

![PCB Before Solder MCU]({{site.baseurl}}/images/2024/corne/pcb_before_mcu.jpg)
![PCB After Solder MCU Top]({{site.baseurl}}/images/2024/corne/pcb_after_mcu_top.jpg)
![PCB After Solder MCU Bottom]({{site.baseurl}}/images/2024/corne/pcb_after_mcu_bottom.jpg)

## The Case

I didn't want to design a case by scratch but had very specific requirements (what a choosing beggar). Below are the few points that mattered most to me:

- Low profile (not bulky)
- No tenting
- Easy access to the power/reset switch for the PCB I chose above

While I was prepared to make some changes to achieve the above requirements, I really wanted to put in the least amount of work. So maybe just something that can be done in the slicer.

### Available options

### The decision

I decided on the case in the link below: (download, zip it up, and add it in this github repo)

https://www.thingiverse.com/thing:4549765

The access to the reset switch was mechanically functional, but the power switch would be completely hidden, thus the front portion was modified in the slicer to open up access to the power slider switch. Then the thickness of the case was reduced by trimming a few mm off the bottom.

### Printing and test fitting

![Case bare]({{site.baseurl}}/images/2024/corne/case_bare.jpg)
![Case with PCB]({{site.baseurl}}/images/2024/corne/case_with_pcb.jpg)
![Case MCU]({{site.baseurl}}/images/2024/corne/case_mcu.jpg)
![Case angle front]({{site.baseurl}}/images/2024/corne/case_angle_front.jpg)
![Case power switch]({{site.baseurl}}/images/2024/corne/case_power.jpg)
![Case reset switch]({{site.baseurl}}/images/2024/corne/case_reset.jpg)
![Case overview]({{site.baseurl}}/images/2024/corne/case_overview.jpg)

## Switch

## Dongle?
