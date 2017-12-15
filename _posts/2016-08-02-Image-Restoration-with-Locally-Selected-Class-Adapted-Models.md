---
layout: post
title: "Image Restoration with Locally Selected Class-Adapted Models"
date: 2016-08-02 09:37:11
categories: arXiv_CV
tags: arXiv_CV Segmentation Face
author: Afonso M. Teodoro, José M. Bioucas-Dias, Mário A. T. Figueiredo
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art algorithms for imaging inverse problems (namely deblurring and reconstruction) are typically iterative, involving a denoising operation as one of its steps. Using a state-of-the-art denoising method in this context is not trivial, and is the focus of current work. Recently, we have proposed to use a class-adapted denoiser (patch-based using Gaussian mixture models) in a so-called plug-and-play scheme, wherein a state-of-the-art denoiser is plugged into an iterative algorithm, leading to results that outperform the best general-purpose algorithms, when applied to an image of a known class (e.g. faces, text, brain MRI). In this paper, we extend that approach to handle situations where the image being processed is from one of a collection of possible classes or, more importantly, contains regions of different classes. More specifically, we propose a method to locally select one of a set of class-adapted Gaussian mixture patch priors, previously estimated from clean images of those classes. Our approach may be seen as simultaneously performing segmentation and restoration, thus contributing to bridging the gap between image restoration/reconstruction and analysis.

##### Abstract (translated by Google)
成像反演问题（即去模糊和重构）的最先进算法通常是迭代的，涉及去噪操作作为其步骤之一。在这种情况下使用最先进的去噪方法不是微不足道的，而且是当前工作的重点。最近，我们已经提出以所谓的即插即用方案使用适应类的降噪器（基于补丁的高斯混合模型），其中将最先进的降噪器插入到迭代算法中，当应用于已知类别的图像（例如面部，文本，脑MRI）时，导致结果优于最佳通用算法。在本文中，我们扩展这种方法来处理被处理的图像来自可能类集合中的一个，或者更重要的是包含不同类的区域的情况。更具体地说，我们提出了一种方法来局部地选择一个类适应的高斯混合补丁先验之一，以前从这些类的清洁图像估计。我们的方法可能被看作是同时执行分割和恢复，从而有助于缩小图像恢复/重建和分析之间的差距。

##### URL
[https://arxiv.org/abs/1605.07003](https://arxiv.org/abs/1605.07003)

##### PDF
[https://arxiv.org/pdf/1605.07003](https://arxiv.org/pdf/1605.07003)

