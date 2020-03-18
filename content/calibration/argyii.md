---
title: ArgyII CMS instructions
weight: 5
---

What you’ll need:
* A computer with Windows, MacOS, or Linux.
* The Reference File for your IT8 target.
* RAW Scan of your IT8 card done in the same way you plan on scanning your boxes/manuals. (Same scanning software, same color bit depth)
* You can download the Reference File for your IT8 target  from the same place you ordered it - http://www.targets.coloraid.de/. Simply scroll down to the section labeled “Download Reference Files” and under R1 looks for the Charger number printed on your IT8 target (example: R131209) and download and unzip that file. 
* Download and install [ArgyII CMS from here][1].

You’ll need to run the command below on your RAW image of the IT8 card, together with the Reference File for your IT8 Target. Within that file you’ll find the chargenumber.txt file for the command below.


```bash
scanin (your-it8-scan).tif (charge-file-number).txt

colprof -qh scanin_output
```

If everything went well you should now have an ICM or ICC file. If not try rescanning your card and repeating the steps. 

[1]: https://www.argyllcms.com/
