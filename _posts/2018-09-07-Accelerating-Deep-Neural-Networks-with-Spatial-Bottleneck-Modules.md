---
layout: post
title: "Accelerating Deep Neural Networks with Spatial Bottleneck Modules"
date: 2018-09-07 17:54:54
categories: arXiv_CV
tags: arXiv_CV CNN Recognition
author: Junran Peng, Lingxi Xie, Zhaoxiang Zhang, Tieniu Tan, Jingdong Wang
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents an efficient module named spatial bottleneck for accelerating the convolutional layers in deep neural networks. The core idea is to decompose convolution into two stages, which first reduce the spatial resolution of the feature map, and then restore it to the desired size. This operation decreases the sampling density in the spatial domain, which is independent yet complementary to network acceleration approaches in the channel domain. Using different sampling rates, we can tradeoff between recognition accuracy and model complexity. 
 As a basic building block, spatial bottleneck can be used to replace any single convolutional layer, or the combination of two convolutional layers. We empirically verify the effectiveness of spatial bottleneck by applying it to the deep residual networks. Spatial bottleneck achieves 2x and 1.4x speedup on the regular and channel-bottlenecked residual blocks, respectively, with the accuracies retained in recognizing low-resolution images, and even improved in recognizing high-resolution images.

##### Abstract (translated by Google)
本文提出了一个有效的模块空间瓶颈，用于加速深度神经网络中的卷积层。核心思想是将卷积分解为两个阶段，首先降低特征映射的空间分辨率，然后将其恢复到所需的大小。该操作降低了空间域中的采样密度，其与信道域中的网络加速方法是独立的但是互补的。使用不同的采样率，我们可以在识别准确度和模型复杂度之间进行权衡。
 作为基本构建块，空间瓶颈可用于替换任何单个卷积层或两个卷积层的组合。我们通过将空间瓶颈应用于深度剩余网络来实证验证空间瓶颈的有效性。空间瓶颈分别在常规和通道瓶颈残余块上实现2倍和1.4倍的加速，在识别低分辨率图像时保持精度，甚至在识别高分辨率图像时得到改善。

##### URL
[http://arxiv.org/abs/1809.02601](http://arxiv.org/abs/1809.02601)

##### PDF
[http://arxiv.org/pdf/1809.02601](http://arxiv.org/pdf/1809.02601)

