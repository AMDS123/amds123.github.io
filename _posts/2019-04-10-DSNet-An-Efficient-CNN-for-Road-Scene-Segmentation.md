---
layout: post
title: "DSNet: An Efficient CNN for Road Scene Segmentation"
date: 2019-04-10 06:46:04
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Deep_Learning
author: Ping-Rong Chen, Hsueh-Ming Hang, Sheng-Wei Chan, Jing-Jhih Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Road scene understanding is a critical component in an autonomous driving system. Although the deep learning-based road scene segmentation can achieve very high accuracy, its complexity is also very high for developing real-time applications. It is challenging to design a neural net with high accuracy and low computational complexity. To address this issue, we investigate the advantages and disadvantages of several popular CNN architectures in terms of speed, storage and segmentation accuracy. We start from the Fully Convolutional Network (FCN) with VGG, and then we study ResNet and DenseNet. Through detailed experiments, we pick up the favorable components from the existing architectures and at the end, we construct a light-weight network architecture based on the DenseNet. Our proposed network, called DSNet, demonstrates a real-time testing (inferencing) ability (on the popular GPU platform) and it maintains an accuracy comparable with most previous systems. We test our system on several datasets including the challenging Cityscapes dataset (resolution of 1024x512) with an mIoU of about 69.1 % and runtime of 0.0147 second per image on a single GTX 1080Ti. We also design a more accurate model but at the price of a slower speed, which has an mIoU of about 72.6 % on the CamVid dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.05022](http://arxiv.org/abs/1904.05022)

##### PDF
[http://arxiv.org/pdf/1904.05022](http://arxiv.org/pdf/1904.05022)

