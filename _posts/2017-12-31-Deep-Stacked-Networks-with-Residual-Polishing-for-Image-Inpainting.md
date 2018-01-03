---
layout: post
title: "Deep Stacked Networks with Residual Polishing for Image Inpainting"
date: 2017-12-31 14:32:27
categories: arXiv_CV
tags: arXiv_CV CNN Quantitative
author: Ugur Demir, Gozde Unal
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks have shown promising results in image inpainting even if the missing area is relatively large. However, most of the existing inpainting networks introduce undesired artifacts and noise to the repaired regions. To solve this problem, we present a novel framework which consists of two stacked convolutional neural networks that inpaint the image and remove the artifacts, respectively. The first network considers the global structure of the damaged image and coarsely fills the blank area. Then the second network modifies the repaired image to cancel the noise introduced by the first network. The proposed framework splits the problem into two distinct partitions that can be optimized separately, therefore it can be applied to any inpainting algorithm by changing the first network. Second stage in our framework which aims at polishing the inpainted images can be treated as a denoising problem where a wide range of algorithms can be employed. Our results demonstrate that the proposed framework achieves significant improvement on both visual and quantitative evaluations.

##### Abstract (translated by Google)
深度神经网络在图像修复中已经显示出有希望的结果，即使缺失面积相对较大。然而，大多数现有的修补网络将不希望的伪像和噪声引入修复的区域。为了解决这个问题，我们提出了一个新的框架，它由两个叠加的卷积神经网络组成，分别对图像进行修复和去除伪像。第一个网络考虑了受损图像的全局结构，粗略地填充了空白区域。然后，第二网络修改修复的图像以消除由第一网络引入的噪声。所提出的框架将问题分解为两个可以单独优化的不同分区，因此可以通过改变第一个网络应用于任何修复算法。在我们的框架中，旨在抛光修复图像的第二阶段可以被看作是可以采用各种算法的去噪问题。我们的研究结果表明，提出的框架在视觉和定量评估方面都取得了显着的进步。

##### URL
[http://arxiv.org/abs/1801.00289](http://arxiv.org/abs/1801.00289)

##### PDF
[http://arxiv.org/pdf/1801.00289](http://arxiv.org/pdf/1801.00289)

