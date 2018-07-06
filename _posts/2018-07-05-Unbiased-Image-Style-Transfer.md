---
layout: post
title: "Unbiased Image Style Transfer"
date: 2018-07-05 09:09:06
categories: arXiv_CV
tags: arXiv_CV Style_Transfer
author: Hyun-Chul Choi, Minseong Kim
mathjax: true
---

* content
{:toc}

##### Abstract
Recent fast image style transferring methods use feed-forward neural networks to generate an output image of desired style strength from the input pair of a content and a target style image. In the existing methods, the image of intermediate style between the content and the target style is obtained by decoding a linearly interpolated feature in encoded feature space. However, there has been no work on analyzing the effectiveness of this kind of style strength interpolation so far. In this paper, we tackle the missing work on the in-depth analysis of style interpolation and propose a method that is more effective in controlling style strength. We interpret the training task of a style transfer network as a regression learning between the control parameter and output style strength. In this understanding, the existing methods are biased due to the fact that training is performed with one-sided data of full style strength (alpha = 1.0). Thus, this biased learning does not guarantee the generation of a desired intermediate style corresponding to the style control parameter between 0.0 and 1.0. To solve this problem of the biased network, we propose an unbiased learning technique which uses unbiased training data and corresponding unbiased loss for alpha = 0.0 to make the feed-forward networks to generate a zero-style image, i.e., content image when alpha = 0.0. Our experimental results verified that our unbiased learning method achieved the reconstruction of a content image with zero style strength, better regression specification between style control parameter and output style, and more stable style transfer that is insensitive to the weight of style loss without additive complexity in image generating process.

##### Abstract (translated by Google)
最近的快速图像样式转移方法使用前馈神经网络从内容的输入对和目标样式图像生成期望样式强度的输出图像。在现有方法中，通过对编码特征空间中的线性插值特征进行解码来获得内容与目标风格之间的中间风格的图像。然而，到目前为止，还没有分析这种样式强度插值的有效性的工作。在本文中，我们解决了对样式插值的深入分析缺失的工作，并提出了一种更有效地控制样式强度的方法。我们将样式转移网络的训练任务解释为控制参数和输出样式强度之间的回归学习。在这种理解中，现有方法存在偏差，因为训练是使用全方位强度（α= 1.0）的单侧数据进行的。因此，这种有偏见的学习并不能保证产生对应于0.0和1.0之间的样式控制参数的所需中间样式。为了解决偏置网络的这个问题，我们提出了一种无偏的学习技术，它使用无偏训练数据和相应的无偏损损失α= 0.0，使前馈网络生成零样式图像，即alpha =时的内容图像0.0。我们的实验结果证实，我们的无偏学习方法实现了样式强度为零的内容图像的重建，样式控制参数和输出样式之间更好的回归规范，以及更加稳定的样式转移，对样式损失的权重不敏感而没有加性复杂性。图像生成过程。

##### URL
[http://arxiv.org/abs/1807.01424](http://arxiv.org/abs/1807.01424)

##### PDF
[http://arxiv.org/pdf/1807.01424](http://arxiv.org/pdf/1807.01424)

