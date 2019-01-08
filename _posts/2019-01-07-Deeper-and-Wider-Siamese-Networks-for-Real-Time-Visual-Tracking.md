---
layout: post
title: "Deeper and Wider Siamese Networks for Real-Time Visual Tracking"
date: 2019-01-07 04:17:43
categories: arXiv_CV
tags: arXiv_CV Attention Tracking CNN
author: Zhang Zhipeng, Peng Houwen, Wang Qiang
mathjax: true
---

* content
{:toc}

##### Abstract
Siamese networks have drawn great attention in visual tracking because of their balanced accuracy and speed. However, the backbone networks used in Siamese trackers are relatively shallow, such as AlexNet [18], which does not fully take advantage of the capability of modern deep neural networks. In this paper, we investigate how to leverage deeper and wider convolutional neural networks to enhance tracking robustness and accuracy. We observe that direct replacement of backbones with existing powerful architectures, such as ResNet [14] and Inception [33], does not bring improvements. The main reasons are that 1)large increases in the receptive field of neurons lead to reduced feature discriminability and localization precision; and 2) the network padding for convolutions induces a positional bias in learning. To address these issues, we propose new residual modules to eliminate the negative impact of padding, and further design new architectures using these modules with controlled receptive field size and network stride. The designed architectures are lightweight and guarantee real-time tracking speed when applied to SiamFC [2] and SiamRPN [20]. Experiments show that solely due to the proposed network architectures, our SiamFC+ and SiamRPN+ obtain up to 9.8%/5.7% (AUC), 23.3%/8.8% (EAO) and 24.4%/25.0% (EAO) relative improvements over the original versions [2, 20] on the OTB-15, VOT-16 and VOT-17 datasets, respectively.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.01660](http://arxiv.org/abs/1901.01660)

##### PDF
[http://arxiv.org/pdf/1901.01660](http://arxiv.org/pdf/1901.01660)

