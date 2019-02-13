---
layout: post
title: "Fast-SCNN: Fast Semantic Segmentation Network"
date: 2019-02-12 17:08:26
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation
author: Rudra P K Poudel, Stephan Liwicki, Roberto Cipolla
mathjax: true
---

* content
{:toc}

##### Abstract
The encoder-decoder framework is state-of-the-art for offline semantic image segmentation. Since the rise in autonomous systems, real-time computation is increasingly desirable. In this paper, we introduce fast segmentation convolutional neural network (Fast-SCNN), an above real-time semantic segmentation model on high resolution image data (1024x2048px) suited to efficient computation on embedded devices with low memory. Building on existing two-branch methods for fast segmentation, we introduce our `learning to downsample' module which computes low-level features for multiple resolution branches simultaneously. Our network combines spatial detail at high resolution with deep features extracted at lower resolution, yielding an accuracy of 68.0% mean intersection over union at 123.5 frames per second on Cityscapes. We also show that large scale pre-training is unnecessary. We thoroughly validate our metric in experiments with ImageNet pre-training and the coarse labeled data of Cityscapes. Finally, we show even faster computation with competitive results on subsampled inputs, without any network modifications.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.04502](http://arxiv.org/abs/1902.04502)

##### PDF
[http://arxiv.org/pdf/1902.04502](http://arxiv.org/pdf/1902.04502)

