+++
title = "Low Tier XSSHUNTER"
date = "2026-04-25"
author = "t66"
description = "Making a version of Iammandatory's XSSHUNTER for a lower tiered VPS"
+++
After a long break I'm finally starting to hunt for bugs again. So I thought the first thing I needed to do was set up and update my tools. I knew I needed a way to test for blind XSS. Iammandatory’s XSSHunter is a tool I used extensively back when I had access to a more capable VPS. Due to my job being slightly inconsistent, I decided to go to a cheaper box, and unfortunately XSSHunter needed more ram. So I decided use a similar stack and build something that would fit my needs.

> repo: https://gitlab.com/ROF618/blnd_xss

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
