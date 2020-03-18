---
title: Rough Profiler
weight: 5
---

## Calibration for Scanning with Rough Profiler

**What you'll need:**

* A computer with either Windows or MacOS
* The Reference File for your IT8 target.
* RAW Scan of your IT8 card done in the same way you plan on scanning your boxes/manuals. (Same scanning software, same color bit depth)
* You can download the Reference File for your IT8 target  from the same place you ordered it - http://www.targets.coloraid.de/. Simply scroll down to the section labeled “Download Reference Files” and under R1 looks for the Charger number printed on your IT8 target (example: R131209) and download and unzip that file. 

* Install Rough Profile scanning software:
  * [For macOS][roughmac]
  * [For Windows (alpha)][roughwin]

Here's how it looks on Windows:
![image](/img/rough-calibration-win1.png?width=40pc)

Here's how it looks on Mac:
![image](/img/rough-calibration-mac.jpg?width=40pc)

**Calibration:**

Upon launching you’ll need to set some options -

1. **Chart Type**: IT8
1. **Test Chart**: point to the RAW image of the card you scanned.
1. **Reference**: Point to the .txt file you unzipped from your downloaded Reference file section mentioned above.
1. **Quality**: High
1. Fill out Manufacturer and Model of the scanner as well as a Profile Name. It can fail if this isn’t done for some silly reason.

**NOTE** if you scanned in your IT8 target in Vuescan in 48-bit Color mode you’ll need to go to the Advanced Tab and set your Test Chart Gamma to 1.0. This is due to Vuescan stripping out the Gamma when set to this setting for some reason. (If you’re unsure just look at your IT8 card scan if it is very dark this is likely the case)

![image](/img/rough-calibration-win2.png?width=40pc)

Once all that is set in Rough Profiler you click **Create It!** and wait a bit. It should now have highlighted lines around your color squares and say finish!

**NOTE** If it errors out you may need to rescan your IT8 card. Make sure it’s straight as it can be, also that you cropped it well and that you didn’t scan it in a higher resolution than 800DPI. Also make sure you filled in the Profile Name, Manufacturer and Model fields. These are common issues in Rough Profiler. If it continues to fail I recommend trying the ArgyIICMS method instead.


![image](/img/rough-calibration-win3.png?width=40pc)

You'll now have an ICM file in the same directory as your scan card. Also be sure to note that when images are converted to other color spaces in post, the engine will need to be set for Microsoft ICM if you used Rough Profiler in Windows. This is due to the fact that currently the Windows version only outputs ICM files and not ICC.

[roughmac]: http://www.jpereira.net/roughprofiler
[roughwin]: http://www.jpereira.net/descargar-rough-profiler-windows
