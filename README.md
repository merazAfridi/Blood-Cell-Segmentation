# Blood-Cell-Segmentation

This repository contains the implementation of blood cell segmentation using various deep learning models. The models implemented here are:

U-Net
R2U-Net (Recurrent Residual U-Net)
Attention U-Net
TernausNet (Modified U-Net with VGG11 backbone)
U-Net++


# Introduction
Blood cell segmentation plays a critical role in the automation of hematological analysis. Proper segmentation of cells from microscopic images is a vital step for various applications such as counting blood cells, diagnosing diseases, and monitoring treatments. The purpose of this project is to explore and compare the performance of different U-Net-based architectures for segmenting blood cells.

#Dataset
The dataset used for training and testing consists of microscopic images of blood cells, each with corresponding ground-truth masks. Each mask labels the regions containing blood cells. For more details on the dataset or to download it, please use the following link:

Download the Blood Cell Dataset from Google Drive:
[Google Drive](https://drive.google.com/file/d/1EYWsgKY8JeZqoGPdjkGpNUIpZnGjakCJ/view?usp=drive_link)

# Architectures

U-Net:

A convolutional neural network designed for biomedical image segmentation. U-Net uses an encoder-decoder structure with skip connections to capture both local and global context.


R2U-Net:

Recurrent Residual U-Net (R2U-Net) enhances U-Net by integrating residual blocks and recurrent convolutions to extract deeper features from the input images. This variant aims to increase the network’s learning capacity.


Attention U-Net:

Attention U-Net incorporates attention mechanisms into the U-Net architecture, allowing the model to focus on important regions of the image, while ignoring irrelevant background details. This improves segmentation accuracy in challenging images.


TernausNet:

TernausNet is a U-Net variant that utilizes a pre-trained VGG11 encoder, which helps the model learn more discriminative features for segmentation. It is known for faster convergence and strong performance.


U-Net++:

U-Net++ refines the U-Net by introducing densely connected convolutional layers between the encoder and decoder, improving the precision of segmentation, especially on complex medical images.


# Results

The following metrics were used to evaluate the performance of each model:

1.Dice Coefficient

2.Jaccard Index

