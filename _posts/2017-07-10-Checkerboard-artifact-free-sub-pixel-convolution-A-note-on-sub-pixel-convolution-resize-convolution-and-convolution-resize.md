---
layout: post
title: "Checkerboard artifact free sub-pixel convolution: A note on sub-pixel convolution, resize convolution and convolution resize"
date: 2017-07-10 16:41:22
categories: arXiv_CV
tags: arXiv_CV
author: Andrew Aitken, Christian Ledig, Lucas Theis, Jose Caballero, Zehan Wang, Wenzhe Shi
mathjax: true
---

* content
{:toc}

##### Abstract
The most prominent problem associated with the deconvolution layer is the presence of checkerboard artifacts in output images and dense labels. To combat this problem, smoothness constraints, post processing and different architecture designs have been proposed. Odena et al. highlight three sources of checkerboard artifacts: deconvolution overlap, random initialization and loss functions. In this note, we proposed an initialization method for sub-pixel convolution known as convolution NN resize. Compared to sub-pixel convolution initialized with schemes designed for standard convolution kernels, it is free from checkerboard artifacts immediately after initialization. Compared to resize convolution, at the same computational complexity, it has more modelling power and converges to solutions with smaller test errors.

##### Abstract (translated by Google)
与解卷积层相关的最突出的问题是在输出图像和密集标签中存在棋盘伪影。为了解决这个问题，已经提出了平滑度约束，后处理和不同的架构设计。 Odena等人突出显示棋盘文物的三个来源：去卷积重叠，随机初始化和丢失函数。在这个笔记中，我们提出了一种称为卷积NN调整大小的子像素卷积的初始化方法。与使用为标准卷积核设计的方案初始化的亚像素卷积相比，在初始化之后它立即从棋盘伪影中解放出来。与卷积调整大小相比，在相同的计算复杂度下，它具有更多的建模能力，并收敛到测试误差更小的解决方案。

##### URL
[https://arxiv.org/abs/1707.02937](https://arxiv.org/abs/1707.02937)

##### PDF
[https://arxiv.org/pdf/1707.02937](https://arxiv.org/pdf/1707.02937)

