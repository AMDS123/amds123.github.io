---
layout: post
title: "Image Super-Resolution via Deterministic-Stochastic Synthesis and Local Statistical Rectification"
date: 2018-09-18 06:50:56
categories: arXiv_CV
tags: arXiv_CV Adversarial Super_Resolution GAN Quantitative Relation
author: Weifeng Ge, Bingchen Gong, Yizhou Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Single image superresolution has been a popular research topic in the last two decades and has recently received a new wave of interest due to deep neural networks. In this paper, we approach this problem from a different perspective. With respect to a downsampled low resolution image, we model a high resolution image as a combination of two components, a deterministic component and a stochastic component. The deterministic component can be recovered from the low-frequency signals in the downsampled image. The stochastic component, on the other hand, contains the signals that have little correlation with the low resolution image. We adopt two complementary methods for generating these two components. While generative adversarial networks are used for the stochastic component, deterministic component reconstruction is formulated as a regression problem solved using deep neural networks. Since the deterministic component exhibits clearer local orientations, we design novel loss functions tailored for such properties for training the deep regression network. These two methods are first applied to the entire input image to produce two distinct high-resolution images. Afterwards, these two images are fused together using another deep neural network that also performs local statistical rectification, which tries to make the local statistics of the fused image match the same local statistics of the groundtruth image. Quantitative results and a user study indicate that the proposed method outperforms existing state-of-the-art algorithms with a clear margin.

##### Abstract (translated by Google)
单图像超分辨率在过去的二十年中一直是一个受欢迎的研究课题，并且最近由于深度神经网络而受到了新的兴趣。在本文中，我们从不同的角度处理这个问题。关于下采样的低分辨率图像，我们将高分辨率图像建模为两个分量的组合，即确定性分量和随机分量。可以从下采样图像中的低频信号恢复确定性分量。另一方面，随机分量包含与低分辨率图像几乎没有相关性的信号。我们采用两种互补的方法来生成这两个组件。虽然生成对抗网络用于随机分量，但确定性分量重构被公式化为使用深度神经网络解决的回归问题。由于确定性分量表现出更清晰的局部方向，我们设计了新的损失函数，用于训练深度回归网络。这两种方法首先应用于整个输入图像，以产生两个不同的高分辨率图像。然后，使用另一个深度神经网络将这两个图像融合在一起，该神经网络还执行局部统计校正，其试图使融合图像的局部统计与地面图像的相同局部统计匹配。定量结果和用户研究表明，所提出的方法优于现有的最先进算法，具有明显的余量。

##### URL
[https://arxiv.org/abs/1809.06557](https://arxiv.org/abs/1809.06557)

##### PDF
[https://arxiv.org/pdf/1809.06557](https://arxiv.org/pdf/1809.06557)

