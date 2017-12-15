---
layout: post
title: "Density Modeling of Images using a Generalized Normalization Transformation"
date: 2016-02-29 21:07:30
categories: arXiv_CV
tags: arXiv_CV
author: Johannes Ballé, Valero Laparra, Eero P. Simoncelli
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a parametric nonlinear transformation that is well-suited for Gaussianizing data from natural images. The data are linearly transformed, and each component is then normalized by a pooled activity measure, computed by exponentiating a weighted sum of rectified and exponentiated components and a constant. We optimize the parameters of the full transformation (linear transform, exponents, weights, constant) over a database of natural images, directly minimizing the negentropy of the responses. The optimized transformation substantially Gaussianizes the data, achieving a significantly smaller mutual information between transformed components than alternative methods including ICA and radial Gaussianization. The transformation is differentiable and can be efficiently inverted, and thus induces a density model on images. We show that samples of this model are visually similar to samples of natural image patches. We demonstrate the use of the model as a prior probability density that can be used to remove additive noise. Finally, we show that the transformation can be cascaded, with each layer optimized using the same Gaussianization objective, thus offering an unsupervised method of optimizing a deep network architecture.

##### Abstract (translated by Google)
我们引入一个参数非线性变换，非常适合从自然图像中高斯化数据。数据是线性变换的，然后每个分量用汇总的活动度量标准化，通过对整数和幂指数的元素和一个常数的加权求和来计算。我们在自然图像数据库上优化完整变换（线性变换，指数，权重，常量）的参数，直接最小化响应的负熵。经过优化的变换对数据进行了实质性的高斯化处理，实现了变换后的组成部分之间的互信息量明显小于ICA和径向高斯化等替代方法。该变换是可微分的，并且可以被高效地倒置，从而在图像上引入密度模型。我们显示这个模型的样本在视觉上与自然图像块的样本类似。我们演示了使用模型作为先验概率密度，可以用来消除加性噪声。最后，我们证明了变换可以级联，每一层都使用相同的高斯化目标进行优化，从而提供了一种无监督的优化深度网络架构的方法。

##### URL
[https://arxiv.org/abs/1511.06281](https://arxiv.org/abs/1511.06281)

##### PDF
[https://arxiv.org/pdf/1511.06281](https://arxiv.org/pdf/1511.06281)

