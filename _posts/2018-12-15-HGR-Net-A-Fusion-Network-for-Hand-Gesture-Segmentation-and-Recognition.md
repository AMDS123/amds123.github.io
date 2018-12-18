---
layout: post
title: "HGR-Net: A Fusion Network for Hand Gesture Segmentation and Recognition"
date: 2018-12-15 20:29:36
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Classification Recognition
author: Amirhossein Dadashzadeh, Alireza Tavakoli Targhi, Maryam Tahmasbi, Majid Mirmehdi
mathjax: true
---

* content
{:toc}

##### Abstract
Robust recognition of hand gestures in real-world applications is still an unaccomplished goal due to many remaining challenges, such as cluttered backgrounds and unconstrained environmental factors. In most existing methods in this field, hand segmentation is a critical step to reduce redundant information in the scene background, in preparation for the hand gesture recognition stage. Therefore, we propose a new two-stage convolutional neural network (CNN) architecture, called HGR-Net, where the first stage performs accurate pixel-level semantic segmentation to determine the hand regions, and the second stage identifies the hand gesture. The segmentation stage architecture is based on the combination of fully convolutional residual network and atrous spatial pyramid pooling. Although the segmentation sub-network is trained without depth information, it is significantly robust against challenges such as illumination variations and complex backgrounds. The recognition stage deploys a two-stream CNN which fuses the information from the RGB and segmented images by combining their deep representations in a new fully connected layer before classification. Extensive experiments on public hand gesture datasets show that our deep architecture achieves almost as good as state-of-the-art performance in segmentation and recognition of static hand gestures, at a fraction of training time, run time, and model size.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1806.05653](http://arxiv.org/abs/1806.05653)

##### PDF
[http://arxiv.org/pdf/1806.05653](http://arxiv.org/pdf/1806.05653)

