---
layout: post
title: "Joint convolutional neural pyramid for depth map super-resolution"
date: 2018-01-03 11:53:34
categories: arXiv_CV
tags: arXiv_CV Salient Super_Resolution CNN
author: Yi Xiao, Xiang Cao, Xianyi Zhu, Renzhi Yang, Yan Zheng
mathjax: true
---

* content
{:toc}

##### Abstract
High-resolution depth map can be inferred from a low-resolution one with the guidance of an additional high-resolution texture map of the same scene. Recently, deep neural networks with large receptive fields are shown to benefit applications such as image completion. Our insight is that super resolution is similar to image completion, where only parts of the depth values are precisely known. In this paper, we present a joint convolutional neural pyramid model with large receptive fields for joint depth map super-resolution. Our model consists of three sub-networks, two convolutional neural pyramids concatenated by a normal convolutional neural network. The convolutional neural pyramids extract information from large receptive fields of the depth map and guidance map, while the convolutional neural network effectively transfers useful structures of the guidance image to the depth image. Experimental results show that our model outperforms existing state-of-the-art algorithms not only on data pairs of RGB/depth images, but also on other data pairs like color/saliency and color-scribbles/colorized images.

##### Abstract (translated by Google)
高分辨率深度图可以从低分辨率深度图推导出来，并且可以在相同场景的附加高分辨率纹理图的引导下进行。最近，具有较大感受域的深度神经网络被证明有益于诸如图像完成的应用。我们的见解是，超分辨率与图像完成类似，只有部分深度值是已知的。在本文中，我们提出了一个联合卷积神经金字塔模型，具有较大的接受场，用于联合深度图超分辨率。我们的模型由三个子网络组成，两个卷积神经金字塔由正常的卷积神经网络连接起来。卷积神经网络从深度图和制导图的大容量接收域中提取信息，而卷积神经网络则有效地将制导图像的有用结构转化为深度图像。实验结果表明，我们的模型不仅在RGB /深度图像的数据对上，而且在颜色/显着性和彩色涂鸦/彩色图像等其他数据对上优于现有的最新算法。

##### URL
[http://arxiv.org/abs/1801.00968](http://arxiv.org/abs/1801.00968)

##### PDF
[http://arxiv.org/pdf/1801.00968](http://arxiv.org/pdf/1801.00968)

