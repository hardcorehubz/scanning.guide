---
title: Rough Profiler
weight: 5
---

## Calibration for Scanning with Rough Profiler

**What you'll need:**

1. A computer: Windows, MacOS, or Linux.
2. An [IT8 Color Card][it8] (choose "R1" option). Download the .it8 file for it as well from the same webpage, you can find the right zip to download by looking for the "Charge" number on your card (example: R131209) and searching for that number on the website. Unzip to somewhere were you can easily find it.
3. Install Rough Profile scanning software:
    [For macOS ][roughmac]
    [For Windows (alpha)][roughwin]

**Calibration:**

1. Test Chart - point to the RAW image of the card you scanned.

Here's how it looks on Windows:
![image](/img/rough-calibration-win1.png?width=40pc)

Here's how it looks on Mac:
![image](/img/rough-calibration-mac.jpg?width=40pc)

2. Fill out Manufacturer and Model.
3. Under **Advanced** make sure **Gamma is set to 1.0**

![image](/img/rough-calibration-win2.png?width=40pc)

4. Once all that is set in Rough Profiler you click **Create It!** and wait a bit
5. It should now have highlighted lines around your color squares and say finish!

![image](/img/rough-calibration-win3.png?width=40pc)

You'll now have an ICM file in the same directory as your scan card. Also be sure to note that when images are converted to other color spaces in post, the engine will need to be set for Microsoft ICM if you used Rough Profiler in Windows. This is due to the fact that currently the Windows version only outputs ICM files and not ICC.

[roughmac]: http://www.jpereira.net/roughprofiler
[roughwin]: http://www.jpereira.net/descargar-rough-profiler-windows
