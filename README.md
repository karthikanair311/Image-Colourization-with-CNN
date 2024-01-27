# Image Colourization with CNN

## Introduction

This notebook comprehends the process of colorizing black and white images using Convolutional Neural Networks (CNNs).

It delves into advanced neural network techniques, particularly emphasizing the role of Resnet in extracting features. This is coupled with a fusion process that integrates a layer following the downsampling or pooling of the input/encoded layer. Subsequently, the process involves decoding using convolution layers via upsampling to generate the colored image output. Moreover, it touches upon advanced image colorization methods like pix2pix GAN and Cycle GAN.

The core of this notebook focuses on an auto-encoder network. Not only does this network serve the primary purpose of image colorization, but it also functions as a generator within the GAN network framework. Thus, mastering this notebook lays the groundwork for understanding more intricate networks and methodologies in the realm of image colorization.

## Aim

The primary aim of this notebook is experimental, exploring the efficacy of a basic auto-encoder in image colorization. While more sophisticated and advanced methods exist for this task, yielding impressive outcomes, this notebook aims to showcase the performance of a fundamental auto-encoder in addressing the challenge of image colorization.

## For Reference

https://ieeexplore.ieee.org/abstract/document/9793234
https://learnopencv.com/convolutional-neural-network-based-image-colorization-using-opencv/
https://www.mdpi.com/2227-7390/8/12/2258
