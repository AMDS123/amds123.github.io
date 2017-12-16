---
layout: post
title: "Efficient and Invariant Convolutional Neural Networks for Dense Prediction"
date: 2017-11-24 18:19:08
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Prediction Recognition
author: Hongyang Gao, Shuiwang Ji
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks have shown great success on feature extraction from raw input data such as images. Although convolutional neural networks are invariant to translations on the inputs, they are not invariant to other transformations, including rotation and flip. Recent attempts have been made to incorporate more invariance in image recognition applications, but they are not applicable to dense prediction tasks, such as image segmentation. In this paper, we propose a set of methods based on kernel rotation and flip to enable rotation and flip invariance in convolutional neural networks. The kernel rotation can be achieved on kernels of 3 $\times$ 3, while kernel flip can be applied on kernels of any size. By rotating in eight or four angles, the convolutional layers could produce the corresponding number of feature maps based on eight or four different kernels. By using flip, the convolution layer can produce three feature maps. By combining produced feature maps using maxout, the resource requirement could be significantly reduced while still retain the invariance properties. Experimental results demonstrate that the proposed methods can achieve various invariance at reasonable resource requirements in terms of both memory and time.

##### Abstract (translated by Google)
卷积神经网络在从诸如图像的原始输入数据提取特征方面显示了巨大的成功。尽管卷积神经网络对输入的平移是不变的，但对于其他变换（包括旋转和翻转）不是不变的。近来已经尝试在图像识别应用中结合更多不变性，但是它们不适用于密集预测任务，如图像分割。在本文中，我们提出了一套基于内核旋转和翻转的方法，以实现卷积神经网络的旋转和翻转不变性。内核旋转可以在3 $ \ times $ 3的内核上实现，而内核翻转可以应用于任何大小的内核。通过旋转八个或四个角度，卷积层可以基于八个或四个不同的内核产生相应数量的特征图。通过使用翻转，卷积层可以产生三个特征图。通过使用maxout组合生成的特征映射，可以显着降低资源需求，同时仍然保持不变性属性。实验结果表明，所提出的方法可以在合理的资源需求下，在内存和时间两个方面达到各种不变性。

##### URL
[https://arxiv.org/abs/1711.09064](https://arxiv.org/abs/1711.09064)

##### PDF
[https://arxiv.org/pdf/1711.09064](https://arxiv.org/pdf/1711.09064)

