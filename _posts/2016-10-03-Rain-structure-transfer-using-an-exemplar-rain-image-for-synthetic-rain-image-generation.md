---
layout: post
title: "Rain structure transfer using an exemplar rain image for synthetic rain image generation"
date: 2016-10-03 06:58:43
categories: arXiv_CV
tags: arXiv_CV
author: Chang-Hwan Son, Xiao-Ping Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
This letter proposes a simple method of transferring rain structures of a given exemplar rain image into a target image. Given the exemplar rain image and its corresponding masked rain image, rain patches including rain structures are extracted randomly, and then residual rain patches are obtained by subtracting those rain patches from their mean patches. Next, residual rain patches are selected randomly, and then added to the given target image along a raster scanning direction. To decrease boundary artifacts around the added patches on the target image, minimum error boundary cuts are found using dynamic programming, and then blending is conducted between overlapping patches. Our experiment shows that the proposed method can generate realistic rain images that have similar rain structures in the exemplar images. Moreover, it is expected that the proposed method can be used for rain removal. More specifically, natural images and synthetic rain images generated via the proposed method can be used to learn classifiers, for example, deep neural networks, in a supervised manner.

##### Abstract (translated by Google)
这封信提出了一个简单的方法，将一个特定的雨图像的雨水结构转换成目标图像。给定典型的雨图像及其相应的蒙板雨图像，随机抽取包括雨型结构的雨斑，从其平均斑块中减去雨斑，得到残余雨斑。接下来，随机选择残余的雨点，然后沿着光栅扫描方向将其添加到给定的目标图像。为了减少目标图像上添加的补丁周围的边界伪影，使用动态编程发现最小误差边界切割，然后在重叠的补丁之间进行混合。我们的实验表明，该方法可以生成具有相似雨形结构的真实雨图像。此外，预计所提出的方法可用于除雨。更具体地说，通过所提出的方法生成的自然图像和合成雨图像可以用于以监督的方式学习分类器，例如深度神经网络。

##### URL
[https://arxiv.org/abs/1610.00427](https://arxiv.org/abs/1610.00427)

##### PDF
[https://arxiv.org/pdf/1610.00427](https://arxiv.org/pdf/1610.00427)

