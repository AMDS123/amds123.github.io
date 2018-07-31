---
layout: post
title: "Texture Mixing by Interpolating Deep Statistics via Gaussian Models"
date: 2018-07-29 10:21:37
categories: arXiv_CV
tags: arXiv_CV Style_Transfer
author: Zi-Ming Wang, Gui-Song Xia, Yi-Peng Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, enthusiastic studies have devoted to texture synthesis using deep neural networks, because these networks excel at handling complex patterns in images. In these models, second-order statistics, such as Gram matrix, are used to describe textures. Despite the fact that these model have achieved promising results, the structure of their parametric space is still unclear, consequently, it is difficult to use them to mix textures. This paper addresses the texture mixing problem by using a Gaussian scheme to interpolate deep statistics computed from deep neural networks. More precisely, we first reveal that the statistics used in existing deep models can be unified using a stationary Gaussian scheme. We then present a novel algorithm to mix these statistics by interpolating between Gaussian models using optimal transport. We further apply our scheme to Neural Style Transfer, where we can create mixed styles. The experiments demonstrate that our method can achieve state-of-the-art results. Because all the computations are implemented in closed forms, our mixing algorithm adds only negligible time to the original texture synthesis procedure.

##### Abstract (translated by Google)
最近，热心研究致力于使用深度神经网络进行纹理合成，因为这些网络在处理图像中的复杂图案方面表现优异。在这些模型中，二阶统计量（如Gram矩阵）用于描述纹理。尽管这些模型已经取得了有希望的结果，但它们的参数空间结构仍然不清楚，因此很难用它们来混合纹理。本文通过使用高斯方案来插入深度神经网络计算的深度统计量来解决纹理混合问题。更确切地说，我们首先揭示现有深度模型中使用的统计数据可以使用平稳高斯方案来统一。然后，我们提出了一种新算法，通过使用最优传输在高斯模型之间进行插值来混合这些统计量。我们进一步将我们的方案应用于神经风格转移，我们可以创建混合风格。实验证明我们的方法可以实现最先进的结果。由于所有计算都是以封闭形式实现的，因此我们的混合算法仅为原始纹理合成过程增加了可忽略的时间。

##### URL
[http://arxiv.org/abs/1807.11035](http://arxiv.org/abs/1807.11035)

##### PDF
[http://arxiv.org/pdf/1807.11035](http://arxiv.org/pdf/1807.11035)

