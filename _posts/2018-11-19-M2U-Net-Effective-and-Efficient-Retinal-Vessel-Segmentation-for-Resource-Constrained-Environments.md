---
layout: post
title: "M2U-Net: Effective and Efficient Retinal Vessel Segmentation for Resource-Constrained Environments"
date: 2018-11-19 14:51:56
categories: arXiv_CV
tags: arXiv_CV Segmentation Inference
author: Tim Laibacher, Tillman Weyde, Sepehr Jalali
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a novel neural network architecture for retinal vessel segmentation that improves over the state of the art on two benchmark datasets, is the first to run in real time on high resolution images, and its small memory and processing requirements make it deployable in mobile and embedded systems. 
 The M2U-Net has a new encoder-decoder architecture that is inspired by the U-Net. It adds pretrained components of MobileNetV2 in the encoder part and novel contractive bottleneck blocks in the decoder part that, combined with bilinear upsampling, drastically reduce the parameter count to 0.55M compared to 31.03M in the original U-Net. 
 We have evaluated its performance against a wide body of previously published results on three public datasets. On two of them, the M2U-Net achieves new state-of-the-art performance by a considerable margin. When implemented on a GPU, our method is the first to achieve real-time inference speeds on high-resolution fundus images. We also implemented our proposed network on an ARM-based embedded system where it segments images in between 0.6 and 15 sec, depending on the resolution. Thus, the M2U-Net enables a number of applications of retinal vessel structure extraction, such as early diagnosis of eye diseases, retinal biometric authentication systems, and robot assisted microsurgery.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.07738](http://arxiv.org/abs/1811.07738)

##### PDF
[http://arxiv.org/pdf/1811.07738](http://arxiv.org/pdf/1811.07738)

