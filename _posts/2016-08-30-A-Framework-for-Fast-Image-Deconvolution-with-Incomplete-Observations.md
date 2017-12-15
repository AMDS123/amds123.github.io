---
layout: post
title: "A Framework for Fast Image Deconvolution with Incomplete Observations"
date: 2016-08-30 17:40:01
categories: arXiv_CV
tags: arXiv_CV
author: Miguel Simões, Luis B. Almeida, José Bioucas-Dias, Jocelyn Chanussot
mathjax: true
---

* content
{:toc}

##### Abstract
In image deconvolution problems, the diagonalization of the underlying operators by means of the FFT usually yields very large speedups. When there are incomplete observations (e.g., in the case of unknown boundaries), standard deconvolution techniques normally involve non-diagonalizable operators, resulting in rather slow methods, or, otherwise, use inexact convolution models, resulting in the occurrence of artifacts in the enhanced images. In this paper, we propose a new deconvolution framework for images with incomplete observations that allows us to work with diagonalized convolution operators, and therefore is very fast. We iteratively alternate the estimation of the unknown pixels and of the deconvolved image, using, e.g., an FFT-based deconvolution method. This framework is an efficient, high-quality alternative to existing methods of dealing with the image boundaries, such as edge tapering. It can be used with any fast deconvolution method. We give an example in which a state-of-the-art method that assumes periodic boundary conditions is extended, through the use of this framework, to unknown boundary conditions. Furthermore, we propose a specific implementation of this framework, based on the alternating direction method of multipliers (ADMM). We provide a proof of convergence for the resulting algorithm, which can be seen as a "partial" ADMM, in which not all variables are dualized. We report experimental comparisons with other primal-dual methods, where the proposed one performed at the level of the state of the art. Four different kinds of applications were tested in the experiments: deconvolution, deconvolution with inpainting, superresolution, and demosaicing, all with unknown boundaries.

##### Abstract (translated by Google)
在图像反卷积问题中，通过FFT对底层算子进行对角化通常会产生非常大的加速。当不完整的观察结果（例如，在未知边界的情况下），标准反卷积技术通常涉及非对角化操作符，导致相当慢的方法，否则使用不精确的卷积模型，导致在增强中出现伪像图片。在本文中，我们提出了一个新的反卷积框架的图像与不完整的观察，使我们能够与对角化卷积算子，因此是非常快的。我们使用例如基于FFT的去卷积方法迭代地交替估计未知像素和解卷积图像。这个框架是处理图像边界的现有方法（如边缘渐变）的高效，高质量替代方案。它可以与任何快速反卷积方法一起使用。我们举一个例子，其中假定周期性边界条件的最先进的方法通过使用这个框架扩展到未知的边界条件。此外，我们基于乘法器的交替方向方法（ADMM）提出了这个框架的具体实现。我们为所得到的算法提供了一个收敛的证明，它可以被看作是一个“部分”的ADMM，其中并不是所有的变量都被二元化。我们报告与其他原始双重方法的实验比较，其中提出的一个在现有技术的水平进行。在实验中测试了四种不同的应用：去卷积，去卷积，修正，超分辨率和去马赛克，所有的边界都是未知的。

##### URL
[https://arxiv.org/abs/1602.01410](https://arxiv.org/abs/1602.01410)

##### PDF
[https://arxiv.org/pdf/1602.01410](https://arxiv.org/pdf/1602.01410)

