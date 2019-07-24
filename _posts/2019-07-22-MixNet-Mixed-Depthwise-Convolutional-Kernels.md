---
layout: post
title: "MixNet: Mixed Depthwise Convolutional Kernels"
date: 2019-07-22 21:49:25
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Classification Detection
author: Mingxing Tan, Quoc V. Le
mathjax: true
---

* content
{:toc}

##### Abstract
Depthwise convolution is becoming increasingly popular in modern efficient ConvNets, but its kernel size is often overlooked. In this paper, we systematically study the impact of different kernel sizes, and observe that combining the benefits of multiple kernel sizes can lead to better accuracy and efficiency. Based on this observation, we propose a new mixed depthwise convolution (MDConv), which naturally mixes up multiple kernel sizes in a single convolution. As a simple drop-in replacement of vanilla depthwise convolution, our MDConv improves the accuracy and efficiency for existing MobileNets on both ImageNet classification and COCO object detection. 
 By integrating MDConv into AutoML search space, we have further developed a new family of models, named as MixNets, which significantly outperform previous models including MobileNetV2 [19] (ImageNet top-1 accuracy +4.2%), ShuffleNetV2 [15] (+3.5%), MnasNet [25] (+1.3%), ProxylessNAS [2] (+2.2%), and FBNet [26] (+2.0%). In particular, our MixNet-L achieves a new state-of-the-art 78.9% ImageNet top-1 accuracy under typical mobile settings (&lt;600M FLOPS). Code is at https://github.com/tensorflow/tpu/tree/master/models/official/mnasnet/mixnet.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.09595](http://arxiv.org/abs/1907.09595)

##### PDF
[http://arxiv.org/pdf/1907.09595](http://arxiv.org/pdf/1907.09595)

