---
layout: post
title: "TOM-Net: Learning Transparent Object Matting from a Single Image"
date: 2018-03-13 06:03:42
categories: arXiv_CV
tags: arXiv_CV Deep_Learning Prediction
author: Guanying Chen, Kai Han, Kwan-Yee K. Wong
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the problem of transparent object matting. Existing image matting approaches for transparent objects often require tedious capturing procedures and long processing time, which limit their practical use. In this paper, we first formulate transparent object matting as a refractive flow estimation problem. We then propose a deep learning framework, called TOM-Net, for learning the refractive flow. Our framework comprises two parts, namely a multi-scale encoder-decoder network for producing a coarse prediction, and a residual network for refinement. At test time, TOM-Net takes a single image as input, and outputs a matte (consisting of an object mask, an attenuation mask and a refractive flow field) in a fast feed-forward pass. As no off-the-shelf dataset is available for transparent object matting, we create a large-scale synthetic dataset consisting of 158K images of transparent objects rendered in front of images sampled from the Microsoft COCO dataset. We also collect a real dataset consisting of 876 samples using 14 transparent objects and 60 background images. Promising experimental results have been achieved on both synthetic and real data, which clearly demonstrate the effectiveness of our approach.

##### Abstract (translated by Google)
本文讨论了透明物体遮挡的问题。现有的用于透明物体的图像消光方法通常需要繁琐的捕获程序和长的处理时间，这限制了它们的实际使用。在本文中，我们首先将透明物体抠像作为折射流估计问题。然后，我们提出了一个深度学习框架，称为TOM-Net，用于学习折射流。我们的框架包括两部分，即用于产生粗略预测的多尺度编码器 - 解码器网络和用于细化的残余网络。在测试时间，TOM-Net将单个图像作为输入，并在快速前馈过程中输出遮罩（包含对象遮罩，衰减遮罩和折射流场）。由于没有现成的数据集可用于透明对象遮挡，因此我们创建了一个大型综合数据集，其中包含从Microsoft COCO数据集中采集的图像前呈现的158K透明对象图像。我们还使用14个透明物体和60个背景图像来收集包含876个样本的真实数据集。合成和真实数据都取得了有希望的实验结果，这清楚地表明了我们方法的有效性。

##### URL
[http://arxiv.org/abs/1803.04636](http://arxiv.org/abs/1803.04636)

##### PDF
[http://arxiv.org/pdf/1803.04636](http://arxiv.org/pdf/1803.04636)

