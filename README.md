## Introduction
This repository contains the implementation of various semantic segmentation models used for understanding urban street scenes in the context of autonomous driving. Semantic segmentation is crucial for the perception systems of self-driving cars, allowing them to classify each pixel of an image into a particular class. Autonomous driving is one of the most actively researched areas in the automotive industry. This project leverages semantic segmentation as a core element for the perception systems, which include components like lidars, cameras, and sensors.

## Dataset
The dataset used for training the models is the Cityscapes Image Pairs, which contains labeled still images from the original videos with semantic segmentation labels. It includes 2975 training images and 500 validation images, each with a dimension of 256x512 pixels.

## Implementation Details
The semantic segmentation models implemented include:
- U-Net
- Fully Convolutional Network (FCN) with VGG16 encoder
- FCN with ResNet50 encoder

These models classify each pixel of an image and use convolutional neural networks (CNNs) for this task. The typical CNN architecture is modified by replacing fully connected layers with convolutional layers to accommodate pixel-wise classification.

## References
Dataset: https://drive.google.com/file/d/15a5yXdisHwrYtyASgFIdOhWCVSoRspOt/view?usp=sharing

Trained models can be found here:
VGG : https://drive.google.com/file/d/1vySMUIpD0EXqUpvqWE4VzXZhVsFu4VOY/view?usp=sharing 
