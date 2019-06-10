---
layout: default
title: RC2014 Classic
sidebar:
  nav: "docs"
---

# RC2014 Classic

![](board1.png)

[Z80 2.1 CPU Module](././Z8021CPU/guide.html)

## Description

The **RC2014 Classic** is a complete, Z80-based 8-bit computer capable of running BASIC and Z80 development tools "out of the box", and CP/M with a little more effort.

It consists of multiple modules; depending on whether you purchased the Bare bones, Starter Kit, or Full Monty, you may need to provide your own components.

This kit requires a serial connection, such as the optional USB-Serial adaptor, to connect to a desktop/laptop computer (PC or Mac) in order to display anything or receive input. To be completely stand-alone, you might want to add the Raspbery Pi Zero Serial mofule, which can connect to a USB keyboard and directly to an HDMI or Composite video display.

## Instructions

Assemble each of the modules below in turn. When you have completed them all, return to this page.

<ul>
<li>[Z80 2.1 CPU Module](././Z8021CPU/guide.html)</li>
<li>Pageable ROM Module</li>
<li>64k RAM Module</li>
<li>Dual Serial SIO/2 Module</li>
<li>Compact Flash Storage Module</li>
<li>Dual Clock Module</li>
<li>Backplane Pro</li>
</ul>

## Final assembly and testing

Now you can carefully place each board into the backplane. The suggested location is as follows:

(diagram)

Connect the serial connection between your computer and the Serial module connector, like this:

(diagram)

Run the necessary software on the computer. See [Communications](./././communications.html) for more information.

Connect the power supply to the backplane. If all is well, the backplane LED will light up. 

## Troubleshooting


## Expanding the RC2014 Classic

The following modules are frequently used with the Classic:

* [DigitalIO Module](digitalio/guide.html)
* Pi Zero Serial Terminal
* Joystick Module

## Upgrade to use CP/M

In order to use CP/M, it is necessary to have the correct ROM and files on the Compact Flash module. I don't know, I'm making this up at the moment.

* To get the ROM...
*  To get the Compact Flash module...