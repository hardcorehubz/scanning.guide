---
title: Scanning standards
weight: 6
---

## 48-Bit Vs. 24-Bit Color (AKA The Great Debate)

For most purposes, outside of photographs or slides, 24-bit color is sufficient for your scans. You are more than welcome to scan at 48-bit just to be safe and capture more information, and in fact the original scanning guide encouraged this. However after research and discussion we’ve had a change of heart on the issue. It’s very unlikely that your scans contain any more useful color information than they would with 24-bit, and are only increasing in file size as well as introducing compatibility issues in certain image viewers.

The purpose of 48-bit is for primarily reducing banding in smooth vignette/gradients while doing color and gradation (curves) adjustments in image editing programs. However the vast majority of game media (Boxes, Manuals, Labels etc.) were screen printed which means the artwork consists of CMYK dots. These are solid color dots mixed together which don’t produce vignettes/gradients.  If you zoom in on a 1200DPI scan at 100% you can easily make out the dots. A zoomed in 1200DPI scan will look a lot like what you’d see with a microscope on the physical item you’re scanning.

We will keep the table of scanning standards as is, but leave it up to you, dear reader, to decide how you want to proceed.

## Scanning standards

| Tier	| Purpose of Tier	| DPI	|Bit Depth	|Format	|Post Processing	|Pre Processing	|ICC Profile	|RAW Files	|Inscan Color Swatches	|Flattening |
|-|-|-|-|-|-------------------|---------------|---------------|-----------|-----------------------|------------|
|Gold / Mastering	| To reproduce scanned media (digitally and physically) as close to the original as possible.	|1200 minimum 	|48	|TIFF + any (lossless) compression	|None - cropping OK	|None	|Calibrated for individual scanner	|Y	|Y	|No - HIGHLY encouraged (copper plates preferred). Media Compressed for 10 mins prior to, then while scanning|
|Silver  |Preserve an artifact with a fair degree of reproduction	|1200	|48	|TIFF + any (lossless) compression	|None - cropping OK	|None	|Calibrated for individual scanner or Using generic profile for specific scanner model  |Y  |N 	|No|
|Bronze	|Best Effort settings	|600	|24	|PNG or TIFF + any (lossless) compression	|None - cropping OK	|None	|Calibrated for individual scanner or  Using generic profile for specific scanner model	|Y	|N	|No|
|Copper	|Catch and catalog all scanned video game related media for later rescanning	|Below 600 true / optical <br/> Any and all interpolated	|Any	|Any	|Any	|Any	|Any	|Y or N	|N	|No|