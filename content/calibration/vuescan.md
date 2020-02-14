---
title: VueScan
weight: 3
---

## Calibration for Scanning with VueScan

### What you'll need:
1. A computer: Windows, MacOS, or Linux.
2. An [IT8 Color Card][it8] (choose "R1" option). Download the .it8 file for it as well from the same webpage, you can find the right zip to download by looking for the "Charge" number on your card (example: R131209) and searching for that number on the website. Unzip to somewhere were you can easily find it.
3. Purchase and install [VueScan][vuescan] scanning software. (Windows, MacOS, Linux compatible).

### Calibrating your Scanner & Settings Setup
**This should be a one-time process for initial setup.**

1. Turn on your scanner and align your Color Card along the edge of your scanner (you want to scan with it perfectly straight, without rotation).
2. Open VueScan app, the rest of the section "Calibrating your Scanner" takes place in this app.
3. On the "Input" tab change:
    1. Options: Professional
    2. Task: Profile Scanner
    3. Bits per pixel: 48 bit RGB
    4. Scan resolution: Custom
    5. Scan dpi: 800 for Epson brand scanners, 900 for Canon brand scanners.
    6. Source: Make sure your scanner is visible / selected.
4. On the "Color" tab change:
    1. Color balance: None
    2. Scanner ICC Profile: Set the location to save your scanner.icc file which you'll soon be creating in the calibration process.
    3. Scanner IT8: Natigate to the "R161209.it8" file you downloaded in Hardware Step 3 section above.

![image](/img/VueScan-calibration1.png)

5. On the bottom left of the app click "Preview".
6. Your image should scan and a scary-looking grid will appear (ignore this grid for now). If your color card isn't upright with text oriented normally, you'll need to rotate it. Rotate your Color Card preview-scan so it is upright (with text oriented normally). The Rotate options are near the bottom right of the VueScan app.
7. Zoom in to the Color Card (magnifying glass is bottom right on the app).
8. Now, it's time to align the grid. Click and drag from black-corner to black-corner, like this:

![image](/img/VueScan-calibration2.png)

9. You may notice it is slightly tilted. It can be hard to get this perfect, but as long as the square color blocks align closely this is fine.
10. From the top menu, choose Profile > Profile Scanner. This will update your scanner.icc file with calibrated settings.
11. Now it's time to do a test scan which will be used to QC the integrity of your calibration. Go back to the "Input" tab to make the following changes:
    1. Task: Scan to File
    2. Media size: Maximum
    3. Bits per pixel: 48 bit RGB
    4. Media: Color
    5. Scan Resolution: 800 dpi (Note: If you're using a Canon scanner set this to 900dpi. Canon scanners operate optimally at intervals of 300dpi.)
    6. Rotation: Optional, but it can be to "None".
    7. Default Folder: Defaults to "Pictures", optional where you want to set it.
12. In the "Crop" tab set "Crop size: Maximum".
13. In the "Output" tab make the following changes:
    1. Uncheck "PDF file".
    2. Check "Raw file".
    3. Tiff file type: "48 bit RGB"
    4. Raw output with: "Scan"

![image](/img/VueScan-calibration3.png)

14. In the upper left app menu choose "File" > "Save Settings".
15. In the bottom left of the app choose "Scan".

[it8]: http://www.targets.coloraid.de/
[vuescan]: https://www.hamrick.com/