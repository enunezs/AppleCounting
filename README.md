# Counting apples from the Minneapple dataset using different image processing techniques.

Assignment for Machine Vision, 2020



## Segmentation using color channels

Simple segmentation based on brightness components.

Images are split, equalized, thresholded and filtered with morphological operations before separated into clusters.


 - Using [RGB](https://github.com/RobotKitchen/AppleCounting/blob/main/Approach1_HSVSegmentation.ipynb) color channels, red channel used as base, and others extracted.
 - Using [HSV](https://github.com/RobotKitchen/AppleCounting/blob/main/Approach1_RedChannelSegmentation.ipynb) color channels, using brightness component.
 - Using [Both](https://github.com/RobotKitchen/AppleCounting/blob/main/Approach1_RGBHSVSegmentation.ipynb) composite approach, using best of the previous.

## Basic CNN implementation from scratch in two parts:

using the [RGB](https://github.com/RobotKitchen/AppleCounting/blob/main/Approach1_HSVSegmentation.ipynb)
and [HSV](https://github.com/RobotKitchen/AppleCounting/blob/main/Approach1_RedChannelSegmentation.ipynb) color channels.


