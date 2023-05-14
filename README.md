# Spinal-segmentation

In this project I applied 4 approaches for spinal segmentation:<br>
* First one is to use classical image processing technique watershed algorithm with other image pre-processing method for increase performance.<br>
* Second one is deep learning technique Unet algorithm, Mask RCNN and YOLOv8 each algorithm applied individually and in these SOTA performance increased.<br>
* Third approach mix classical approach with deep learning approach using watershed to create aground masks for Unet in next step.<br>
* Finally approach is mixed between two deep learning SOTA so, in first step applied YOLOv8 to segment spinal then crop each image with its segments to use it as input for Unet.
