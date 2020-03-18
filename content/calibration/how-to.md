---
title: How to
weight: 2
---

The first step to calibration is getting a scan of your IT8 card. If you have gone through the [Software](/software) part of the guide,you should be able to use Canon, Epson, or Vuescan scanning software to get a RAW scan of your card. 600-800DPI are recommended as the calibration software sometimes has issues with high resolution scans at 1200DPI or higher. Crop around the card so there’s no whitespace. If you crop into the card a bit it’s okay as long as it’s within the initial grey border. 

The biggest key to this is to scan your IT8 target in exactly the same way you plan to scan your boxes/manuals etc. So if you’re planning on scanning 24-bit in Epson Scan, you’ll need to scan your IT8 target the exact same way. If you’re planning on doing 48-bit sometimes as well then you’ll need to scan and calibrate a separate ICM file for that. It’s really up to how you want to do it. For most users just one calibration file will be all that’s needed because you’ll likely always use the same settings when scanning.

Your scan should look quite dark and somewhat similar to this image:

![image](/img/vuescanraw.jpg?width=40pc)

Now that you a RAW Scan you need to run it through calibration software. Here are a few options we recommend:

2. [Rough Profiler (Windows & Mac)][2]
3. [ArgyII Color Management System (Linux)][3]

The output from Rough Profiler/ArgyIICMS can vary, but all will greatly improve the color accuracy of your scans. Pick the solution that works for you. There is a way to benchmark your results to see which is technically more correct, see [this tutorial][4].

[1]: /calibration/vuescan
[2]: https://www.preservegames.org/2018/08/calibration-for-scanning-with-rough.html
[3]: /calibration/argyii
[4]: /calibration/benchmark
[10]: https://archive.org/details/canon9000fmarkiiiccicm