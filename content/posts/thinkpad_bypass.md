+++
title = "Thinkpad Supervisor Password Bypass"
date = "2026-02-09"
author = "t66"
description = "After a Fedora update the administrator password was triggered and I was locked out of everything, including the BIOS"
+++
Sometime in December of 2025 I updated my Fedora 40 system and something must have triggered the Supervisor Password(SP). This happened at the same time when my storage had become full. With the disk full and the SP enabled, I was stuck in a boot loop. 

With the SP, the system would only get past the GRUB menu and prompt for the SP. The system allowed for me to simply hit enter, and it would take you to the BIOS settings but the system did not allow for any changes to be made.


![error](/img/error1.jpg)

After a couple of hours of research, I found out I was not the only one who had been locked out of their system due to the SP. Due to the significant resale market for Thinkpads and the fact that many of those used Thinkpads come from companies. Those companies usually enable the SP to lock down the computers(rightfully so) and most of the resellers do not provide or have the passwords. 

Enter the kindness of complete strangers. During my research I came across a Reddit page where the OP had the same problem as mine and they resolved it with a Python script they found on a forum. I signed up and I can't say enough about how helpful to devs on Badcaps were. They provided a detailed step by step guide to patch the BIOS using their Python script and a CH341A EEPROM Programmer. 

> forum: https://www.badcaps.net/forum

I ordered the programmer and signed up for a monthly subscription to Badcaps. When the programmer arrived I had the script downloaded and ready to rock. Now I should say that I had a problem with a previous laptop. The keyboard wasn't working and long story short replacing the keyboard did not solve the problem. I found out I needed to resauder a chip and I royally messed up the MOBO. Since then, working on hardware has made me slightly nervous. So I checked and rechecked the clips on the programmer. 

![clip](/img/clip.jpg)
![programmer](/img/programmer.jpg)

I ran the exploit and it unfortunately did not bypass the need for the SP. I promptly signed back on to the Badcaps forum and started digging for the source of my problem. Turns out the exploit needs to be patched with with some specific information from the machine that is locked out. I provided serial number, make, full model number, and MOBO model number. They gave me the patched exploit and I reran the script. 

Boom, worked first time and I got by laptop back. Just want to give one last shout out to Badcaps for saving me a lot of headache.



