---
layout: post
title: "Hardware-Efficient Guided Image Filtering For Multi-Label Problem"
date: 2018-02-28 07:27:43
categories: arXiv_CV
tags: arXiv_CV Knowledge
author: Longquan Dai, Mengke Yuan, Zechao Li, Xiaopeng Zhang, Jinhui Tang
mathjax: true
---

* content
{:toc}

##### Abstract
The Guided Filter (GF) is well-known for its linear complexity. However, when filtering an image with an n-channel guidance, GF needs to invert an n x n matrix for each pixel. To the best of our knowledge existing matrix inverse algorithms are inefficient on current hardwares. This shortcoming limits applications of multichannel guidance in computation intensive system such as multi-label system. We need a new GF-like filter that can perform fast multichannel image guided filtering. Since the optimal linear complexity of GF cannot be minimized further, the only way thus is to bring all potentialities of current parallel computing hardwares into full play. In this paper we propose a hardware-efficient Guided Filter (HGF), which solves the efficiency problem of multichannel guided image filtering and yields competent results when applying it to multi-label problems with synthesized polynomial multichannel guidance. Specifically, in order to boost the filtering performance, HGF takes a new matrix inverse algorithm which only involves two hardware-efficient operations: element-wise arithmetic calculations and box filtering. In order to break the linear model restriction, HGF synthesizes a polynomial multichannel guidance to introduce nonlinearity. Benefiting from our polynomial guidance and hardware-efficient matrix inverse algorithm, HGF not only is more sensitive to the underlying structure of guidance but also achieves the fastest computing speed. Due to these merits, HGF obtains state-of-the-art results in terms of accuracy and efficiency in the computation intensive multi-label

##### Abstract (translated by Google)
导向滤波器（GF）以其线性复杂性而闻名。但是，当用n通道制导滤波图像时，GF需要为每个像素反转n×n矩阵。据我们所知，现有的矩阵逆算法在当前的硬件上效率低下。这个缺点限制了多通道引导在多标签系统等计算密集型系统中的应用。我们需要一个可以执行快速多通道图像引导滤波的新型GF滤波器。由于GF的最佳线性复杂度不能进一步降低，因此唯一的方法是充分发挥当前并行计算硬件的所有潜力。在本文中，我们提出了一种硬件高效的导向滤波器（HGF），该算法解决了多通道引导图像滤波的效率问题，并且在将其应用于具有合成多项式多通道引导的多标签问题时产生了令人满意的结果。具体而言，为了提高滤波性能，HGF采用了一种新的矩阵逆算法，其只涉及两个硬件高效的操作：逐元算术计算和盒式滤波。为了打破线性模型限制，HGF合成多项式多通道引导以引入非线性。受益于我们的多项式制导和硬件高效矩阵逆算法，HGF不仅对制导的基础结构更为敏感，而且还实现了最快的计算速度。由于这些优点，HGF在计算密集型多标签的准确性和效率方面获得了最新的结果

##### URL
[http://arxiv.org/abs/1803.00005](http://arxiv.org/abs/1803.00005)

##### PDF
[http://arxiv.org/pdf/1803.00005](http://arxiv.org/pdf/1803.00005)

