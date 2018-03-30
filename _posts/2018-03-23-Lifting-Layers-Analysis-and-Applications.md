---
layout: post
title: "Lifting Layers: Analysis and Applications"
date: 2018-03-23 05:47:50
categories: arXiv_CV
tags: arXiv_CV Image_Classification Optimization Classification Deep_Learning
author: Peter Ochs, Tim Meinhardt, Laura Leal-Taixe, Michael Moeller
mathjax: true
---

* content
{:toc}

##### Abstract
The great advances of learning-based approaches in image processing and computer vision are largely based on deeply nested networks that compose linear transfer functions with suitable non-linearities. Interestingly, the most frequently used non-linearities in imaging applications (variants of the rectified linear unit) are uncommon in low dimensional approximation problems. In this paper we propose a novel non-linear transfer function, called lifting, which is motivated from a related technique in convex optimization. A lifting layer increases the dimensionality of the input, naturally yields a linear spline when combined with a fully connected layer, and therefore closes the gap between low and high dimensional approximation problems. Moreover, applying the lifting operation to the loss layer of the network allows us to handle non-convex and flat (zero-gradient) cost functions. We analyze the proposed lifting theoretically, exemplify interesting properties in synthetic experiments and demonstrate its effectiveness in deep learning approaches to image classification and denoising.

##### Abstract (translated by Google)
基于学习的方法在图像处理和计算机视觉领域的巨大进步主要基于深度嵌套网络，该网络构成具有合适非线性的线性传递函数。有趣的是，成像应用中最常用的非线性（整流线性单元的变体）在低维近似问题中并不常见。在本文中，我们提出了一种新颖的非线性传递函数，称为提升，它是由凸优化中的相关技术激发的。提升层增加了输入的维数，当与完全连接的层结合时自然产生线性样条，从而缩小了低维和高维近似问题之间的差距。此外，将提升操作应用于网络的丢失层允许我们处理非凸和平坦（零梯度）成本函数。我们从理论上分析了提出的提升问题，举例说明了合成实验中有趣的属性，并展示了它在图像分类和去噪的深度学习方法中的有效性。

##### URL
[https://arxiv.org/abs/1803.08660](https://arxiv.org/abs/1803.08660)

##### PDF
[https://arxiv.org/pdf/1803.08660](https://arxiv.org/pdf/1803.08660)

