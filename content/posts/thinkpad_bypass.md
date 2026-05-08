+++
title = "Thinkpad Bypass"
date = "2026-01-10"
author = "t66"
description = "After a Fedora update the administrator password was triggered and I was locked out of everything, including the BIOS"
+++
Sometime in December of 2025 I updated my Fedora 40 system and something must have triggered the Supervisor Password(SP). This happened at the same time when my storage had become full. With the disk full and the SP enabled, I was stuck in a boot loop. 

With the SP, the system would only get past the GRUB menu and prompt for the SP. The system allowed for me to simply hit enter, and it would take you to the BIOS settings but the system did not allow for any changes to the settings.

![error](/img/error.jpg)

After a couple of hours of research, I found out I was not the only one who had been locked out of their system due to the SP. 

> forum: https://www.badcaps.net/forum

# Installation:
1. `python3 -m venv venv &&`
1. `pip install -r requirements.txt`
1. `source venv/bin/activate &&`
1. `uvicorn app:app --host 0.0.0.0 --port 8000 --workers 1`

 
* decided to receive callbacks from payloads, correlate the callbacks to specific projects/identifier, store the data, and notify admin


Sed a leo id risus venenatis vulputate non quis nulla. Aenean nisl quam, lacinia pulvinar orci sit amet, eleifend eleifend dui. Nulla tempor ligula leo, eu vehicula quam condimentum a. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Nulla gravida tristique nunc sed semper. Morbi nec felis odio.

- Sed efficitur, lacus ac scelerisque pellentesque, lectus risus dignissim nisl, fermentum semper lectus diam eget lacus.
- Nunc ornare purus enim, id eleifend mauris vestibulum volutpat.
- Aenean facilisis ut ipsum condimentum ultrices.
- Fusce sed metus vulputate, lobortis purus et, finibus purus. Suspendisse quis posuere lorem. Vivamus vulputate nec risus in pulvinar.
