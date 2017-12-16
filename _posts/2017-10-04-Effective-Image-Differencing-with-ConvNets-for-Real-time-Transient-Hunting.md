---
layout: post
title: "Effective Image Differencing with ConvNets for Real-time Transient Hunting"
date: 2017-10-04 00:02:02
categories: arXiv_CV
tags: arXiv_CV Survey CNN Detection
author: Nima Sedaghat, Ashish Mahabal
mathjax: true
---

* content
{:toc}

##### Abstract
Large sky surveys are increasingly relying on image subtraction pipelines for real-time (and archival) transient detection. In this process one has to contend with varying PSF, small brightness variations in many sources, as well as artifacts resulting from saturated stars, and, in general, matching errors. Very often the differencing is done with a reference image that is deeper than individual images and the attendant difference in noise characteristics can also lead to artifacts. We present here a deep-learning approach to transient detection that encapsulates all the steps of a traditional image subtraction pipeline -- image registration, background subtraction, noise removal, psf matching, and subtraction -- into a single real-time convolutional network. Once trained the method works lighteningly fast, and given that it does multiple steps at one go, the advantages for multi-CCD, fast surveys like ZTF and LSST are obvious.

##### Abstract (translated by Google)
大型天空调查越来越依赖图像相减管线来进行实时（和归档）的瞬态检测。在这个过程中，人们必须面对不同的PSF，许多来源的小的亮度变化，以及由饱和恒星产生的伪影，一般来说，匹配误差。很多时候，差分是通过比单个图像更深的参考图像来完成的，并且随之而来的噪声特性差异也会导致伪影。我们在这里介绍一种瞬态检测的深度学习方法，将传统图像减法流水线的所有步骤（图像配准，背景减除，噪声去除，psf匹配和减法）封装到单个实时卷积网络中。一旦训练完成，该方法的工作速度非常快，而且由于它一次完成多个步骤，因此多CCD，ZTF和LSST等快速调查的优势是显而易见的。

##### URL
[https://arxiv.org/abs/1710.01422](https://arxiv.org/abs/1710.01422)

##### PDF
[https://arxiv.org/pdf/1710.01422](https://arxiv.org/pdf/1710.01422)

