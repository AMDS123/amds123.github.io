---
layout: post
title: "3D Segmentation with Exponential Logarithmic Loss for Highly Unbalanced Object Sizes"
date: 2018-08-31 22:42:12
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Deep_Learning
author: Ken C. L. Wong, Mehdi Moradi, Hui Tang, Tanveer Syeda-Mahmood
mathjax: true
---

* content
{:toc}

##### Abstract
With the introduction of fully convolutional neural networks, deep learning has raised the benchmark for medical image segmentation on both speed and accuracy, and different networks have been proposed for 2D and 3D segmentation with promising results. Nevertheless, most networks only handle relatively small numbers of labels (&lt;10), and there are very limited works on handling highly unbalanced object sizes especially in 3D segmentation. In this paper, we propose a network architecture and the corresponding loss function which improve segmentation of very small structures. By combining skip connections and deep supervision with respect to the computational feasibility of 3D segmentation, we propose a fast converging and computationally efficient network architecture for accurate segmentation. Furthermore, inspired by the concept of focal loss, we propose an exponential logarithmic loss which balances the labels not only by their relative sizes but also by their segmentation difficulties. We achieve an average Dice coefficient of 82% on brain segmentation with 20 labels, with the ratio of the smallest to largest object sizes as 0.14%. Less than 100 epochs are required to reach such accuracy, and segmenting a 128x128x128 volume only takes around 0.4 s.

##### Abstract (translated by Google)
随着完全卷积神经网络的引入，深度学习提高了医学图像分割的速度和准确度的基准，并且已经提出了用于2D和3D分割的不同网络，并且具有有希望的结果。然而，大多数网络仅处理相对较少数量的标签（＆lt; 10），并且在处理高度不平衡的对象尺寸方面的工作非常有限，尤其是在3D分割中。在本文中，我们提出了一种网络架构和相应的损失函数，它们可以改善非常小的结构的分割。通过结合跳过连接和深度监督三维分割的计算可行性，我们提出了一种快速收敛和计算有效的网络架构，以实现精确分割。此外，受焦点损失概念的启发，我们提出了一种指数对数损失，它不仅通过它们的相对大小而且通过它们的分割困难来平衡标记。我们使用20个标签对大脑分割实现平均Dice系数为82％，最小对象大小与最大对象大小的比率为0.14％。要达到这样的精度，需要不到100个时期，并且分割128x128x128音量只需要大约0.4秒。

##### URL
[http://arxiv.org/abs/1809.00076](http://arxiv.org/abs/1809.00076)

##### PDF
[http://arxiv.org/pdf/1809.00076](http://arxiv.org/pdf/1809.00076)

