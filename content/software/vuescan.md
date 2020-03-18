---
title: VueScan
weight: 3
---

## Scanning RAW Images with VueScan

Vuescan is really only recommended when you’re unable to use your built in scanner software such as Epson Scan or CanoScan. This is due to the fact that the manufacturer's software is tuned to get the best results from their own hardware and it’s also free. However this isn’t always possible with some older scanner models or when using Linux. Vuescan can still be used but it’s a bit trickier to use and might be unstable. It’s also unfortunately not free and for our uses you’ll need to purchase the Professional Edition for it’s RAW scanning capabilities. Below are instructions on properly configuring Vuescan for our uses.

Open up VueScan and make sure to set the Input tab with the following settings. Also below is a screenshot of how it _might look_ (Options differ depending on scanner model used).

1. **Options**: Professional
1. **Task**: Scan to File
1. **Bits per pixel**: 24 bit RGB (You can do up to 48 bit RGB if you like but it is not required. Also a big GOTCHA with Vuescan and 48-bit is that if you cannot create an IT8 profile for your scanner DO NOT scan in 48-bit. Vuescan’s 48-bit RAW scans alters the curves and gamma of your scans that are difficult to fix without a proper IT8 calibration. Please only use 24-bit if you’re not going to do IT8 calibration!)
1. **Scan resolution**: Custom
1. **Scan DPI**: 1200DPI or 1600DPI (Depends what your scanner will allow you to pick, go 1200 if you can)
1. **Source**: Make sure your scanner is visible / selected.


![image](/img/VueScan1.png)

1. Next ensure the “Crop” tab is set to “**Crop size**: Manual”.
1. Finally in the “**Output”** tab make the following changes:
1. Make sure “**Raw file**” is the only thing checked for file type.
1. **Raw file type**: 24 bit (You can do up to 48 bit RGB if you like but it is not required.)
1. **Raw output with**: Scan
1. **Raw Compression**: Off

![image](/img/VueScan2.png)

11. **Make sure to save your settings.**

In the bottom left of the app choose “**Preview**” to see your scan, this might not look like your final output, however don’t worry if the preview looks off, go ahead and draw your cropping box around your image and select the Scan button. Double check that your scanned image is the proper DPI and color bit depth and you’re good to go!
