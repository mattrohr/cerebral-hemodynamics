# Calibration
## Zyla sCMOS Minimum Resolution and Field of View; Blue stimulation laser dimensions
![resolution calculation](https://www.thorlabs.com/images/TabImages/TestTargetEqMD.jpg)\
Therefore,  group 2 element 2's resolution is 4.49 line pairs per millimeter. The width of a line pair is then 1 / 4.49 = 0.222717149 millimeters. This distance was applied using [distance_tool.m](./distance_tool.m), and used to calibrate field of view and laser spot dimensions.

![stimulation (blue) laser dimensions](https://i.imgur.com/Hdq7onj.png)\
*Fig. 3: [Andor Zyla 4.2 sCMOS Camera](https://andor.oxinst.com/products/scmos-camera-series/zyla-4-2-scmos) image of blue stimulation laser ([Laserglow R471003FX](https://www.laserglow.com/product/R47-M-473-nm-DPSS-Laser-System)) illuminating group 2 element 2 on [Thorlabs R1DS1P U.S. Air Force Target](https://www.thorlabs.com/thorproduct.cfm?partnumber=R1DS1P).*

Note: This calibration won't account for brain curvature relative to objective lens.

**pixel size** specified by manufacturer (i.e. Andor): **6.5 µm by 6.5 µm**\
**resolution** specified by manufacturer (i.e. Andor): **2048 pixels by 2048 pixels**\
**sensor size** = pixel size * resolution = **13.3 mm by 13.3 mm**\
**focal length** specified by manufacturer (i.e. Thorlabs): **18 mm**\
**working distance** specified by manufacturer (i.e. Thorlabs): **7.5 mm**\
![Zyla optical schematic](https://i.imgur.com/7rya6hb.png)\
*Fig. 4: distance schematic.*