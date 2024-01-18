---
title: Exporting
description: 
published: true
date: 2024-01-18T21:03:34.808Z
tags: 
editor: markdown
dateCreated: 2024-01-18T21:03:34.808Z
---

# Exporting Chips from Adobe Animate

## 1. Find chip by ID
Select Library at the top right of Adobe Animate.

Sort by "Linkage".  The last 4 numbers in the actionscript linkage is the chip ID.

Select your chip.

![exporting_4.png](/development/exporting/exporting_4.png)

## 2. Review
Look over the chip.  Do you see any defects you can fix?  If you can, fix it, if you cannot fix it you should [open an issue on Github](https://github.com/SitekickRemastered/Art/issues/new/choose) then move on to the next chip.

## 3. Export
Go to File > Export > Export Image (Legacy)...

![exporting_1.png](/development/exporting/exporting_1.png)

Find your chip folder (Example: \Art\Unity\Assets\Chips\0001-0100\Chip_0001\Sprites\)

If there is only one asset for this chip, name your chip chip_0001_base.png and press Save.

![exporting_2.png](/development/exporting/exporting_2.png)

In the Export window, you MUST select a resolution of 500 dpi, include minimum image area, 32 bit colors, and smoothing.

Press Export.  This should save your settings between exports.

![exporting_3.png](/development/exporting/exporting_3.png)