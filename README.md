# Counting apples from the [Minneapple dataset](https://conservancy.umn.edu/handle/11299/206575) 


*Made in colaboration with Emil Delvaux*


My first proper crash into neural networks.



## Segmentation using color channels

Simple segmentation based on brightness components.

Images are split, equalized, thresholded and filtered with morphological operations before separated into clusters.


 - Using [RGB](https://github.com/RobotKitchen/AppleCounting/blob/main/Approach1_HSVSegmentation.ipynb) color channels, red channel used as base, and others extracted.
 - Using [HSV](https://github.com/RobotKitchen/AppleCounting/blob/main/Approach1_RedChannelSegmentation.ipynb) color channels, using brightness component.
 - Using [Both](https://github.com/RobotKitchen/AppleCounting/blob/main/Approach1_RGBHSVSegmentation.ipynb) composite approach, using best of the previous.

## Basic CNN implementation from scratch in two parts:

 - [Design and training](https://github.com/RobotKitchen/AppleCounting/blob/main/Approach2_MachineTraining.ipynb) of the CNN, using the counting dataset from Minneapple. Structure and weights saved for later.
 - [Using the CNN](https://github.com/RobotKitchen/AppleCounting/blob/main/Approach2_Counter.ipynb). Splitting the image into chunks, feeding each one into the trained network and summing up the total of apples.



Overall results are... not the greatest, but as alearning experience was extremely rewarding.

