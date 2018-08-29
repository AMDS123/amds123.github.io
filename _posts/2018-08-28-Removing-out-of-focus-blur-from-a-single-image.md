---
layout: post
title: "Removing out-of-focus blur from a single image"
date: 2018-08-28 08:28:23
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Guodong Xu, Chaoqiang Liu, Hui Ji
mathjax: true
---

* content
{:toc}

##### Abstract
Reproducing an all-in-focus image from an image with defocus regions is of practical value in many applications, eg, digital photography, and robotics. Using the output of some existing defocus map estimator, existing approaches first segment a de-focused image into multiple regions blurred by Gaussian kernels with different variance each, and then de-blur each region using the corresponding Gaussian kernel. In this paper, we proposed a blind deconvolution method specifically designed for removing defocus blurring from an image, by providing effective solutions to two critical problems: 1) suppressing the artifacts caused by segmentation error by introducing an additional variable regularized by weighted $\ell_0$-norm; and 2) more accurate defocus kernel estimation using non-parametric symmetry and low-rank based constraints on the kernel. The experiments on real datasets showed the advantages of the proposed method over existing ones, thanks to the effective treatments of the two important issues mentioned above during deconvolution.

##### Abstract (translated by Google)
从具有散焦区域的图像再现全聚焦图像在许多应用中具有实用价值，例如数字摄影和机器人技术。使用一些现有散焦图估计器的输出，现有方法首先将去聚焦图像分割成由高斯核模糊的多个区域，每个区域具有不同的方差，然后使用相应的高斯核对每个区域进行去模糊。在本文中，我们提出了一种专门设计用于从图像中去除散焦模糊的盲去卷积方法，通过为两个关键问题提供有效的解决方案：1）通过引入由加权$ \ ell_0 $规范化的附加变量来抑制由分割错误引起的伪像。 -规范; 2）使用非参数对称和基于低秩的约束对内核进行更精确的散焦核估计。实际数据集上的实验表明，所提出的方法优于现有方法，这要归功于在解卷积过程中对上述两个重要问题的有效处理。

##### URL
[http://arxiv.org/abs/1808.09166](http://arxiv.org/abs/1808.09166)

##### PDF
[http://arxiv.org/pdf/1808.09166](http://arxiv.org/pdf/1808.09166)

