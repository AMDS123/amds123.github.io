---
layout: post
title: "ASCNet: Adaptive-Scale Convolutional Neural Networks for Multi-Scale Feature Learning"
date: 2019-07-07 07:52:24
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation
author: Mo Zhang, Jie Zhao, Xiang Li, Li Zhang, Quanzheng Li
mathjax: true
---

* content
{:toc}

##### Abstract
Extracting multi-scale information is key to semantic segmentation. However, the classic convolutional neural networks (CNNs) encounter difficulties in achieving multi-scale information extraction: expanding convolutional kernel incurs the high computational cost and using maximum pooling sacrifices image information. The recently developed dilated convolution solves these problems, but with the limitation that the dilation rates are fixed and therefore the receptive field cannot fit for all objects with different sizes in the image. We propose an adaptivescale convolutional neural network (ASCNet), which introduces a 3-layer convolution structure in the end-to-end training, to adaptively learn an appropriate dilation rate for each pixel in the image. Such pixel-level dilation rates produce optimal receptive fields so that the information of objects with different sizes can be extracted at the corresponding scale. We compare the segmentation results using the classic CNN, the dilated CNN and the proposed ASCNet on two types of medical images (The Herlev dataset and SCD RBC dataset). The experimental results show that ASCNet achieves the highest accuracy. Moreover, the automatically generated dilation rates are positively correlated to the sizes of the objects, confirming the effectiveness of the proposed method.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.03241](http://arxiv.org/abs/1907.03241)

##### PDF
[http://arxiv.org/pdf/1907.03241](http://arxiv.org/pdf/1907.03241)

