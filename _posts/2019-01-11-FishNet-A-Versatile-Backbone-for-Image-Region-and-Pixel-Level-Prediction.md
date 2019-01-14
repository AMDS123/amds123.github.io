---
layout: post
title: "FishNet: A Versatile Backbone for Image, Region, and Pixel Level Prediction"
date: 2019-01-11 06:43:56
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Image_Classification Classification Prediction Detection
author: Shuyang Sun, Jiangmiao Pang, Jianping Shi, Shuai Yi, Wanli Ouyang
mathjax: true
---

* content
{:toc}

##### Abstract
The basic principles in designing convolutional neural network (CNN) structures for predicting objects on different levels, e.g., image-level, region-level, and pixel-level are diverging. Generally, network structures designed specifically for image classification are directly used as default backbone structure for other tasks including detection and segmentation, but there is seldom backbone structure designed under the consideration of unifying the advantages of networks designed for pixel-level or region-level predicting tasks, which may require very deep features with high resolution. Towards this goal, we design a fish-like network, called FishNet. In FishNet, the information of all resolutions is preserved and refined for the final task. Besides, we observe that existing works still cannot \emph{directly} propagate the gradient information from deep layers to shallow layers. Our design can better handle this problem. Extensive experiments have been conducted to demonstrate the remarkable performance of the FishNet. In particular, on ImageNet-1k, the accuracy of FishNet is able to surpass the performance of DenseNet and ResNet with fewer parameters. FishNet was applied as one of the modules in the winning entry of the COCO Detection 2018 challenge. The code is available at https://github.com/kevin-ssy/FishNet.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.03495](http://arxiv.org/abs/1901.03495)

##### PDF
[http://arxiv.org/pdf/1901.03495](http://arxiv.org/pdf/1901.03495)

