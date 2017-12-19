---
layout: post
title: "Manitest: Are classifiers really invariant?"
date: 2015-07-23 15:36:50
categories: arXiv_CV
tags: arXiv_CV CNN Recognition
author: Alhussein Fawzi, Pascal Frossard
mathjax: true
---

* content
{:toc}

##### Abstract
Invariance to geometric transformations is a highly desirable property of automatic classifiers in many image recognition tasks. Nevertheless, it is unclear to which extent state-of-the-art classifiers are invariant to basic transformations such as rotations and translations. This is mainly due to the lack of general methods that properly measure such an invariance. In this paper, we propose a rigorous and systematic approach for quantifying the invariance to geometric transformations of any classifier. Our key idea is to cast the problem of assessing a classifier's invariance as the computation of geodesics along the manifold of transformed images. We propose the Manitest method, built on the efficient Fast Marching algorithm to compute the invariance of classifiers. Our new method quantifies in particular the importance of data augmentation for learning invariance from data, and the increased invariance of convolutional neural networks with depth. We foresee that the proposed generic tool for measuring invariance to a large class of geometric transformations and arbitrary classifiers will have many applications for evaluating and comparing classifiers based on their invariance, and help improving the invariance of existing classifiers.

##### Abstract (translated by Google)
不变几何变换是许多图像识别任务中的自动分类器的非常理想的特性。然而，目前还不清楚在何种程度上最先进的分类器对旋转和翻译等基本转换是不变的。这主要是由于缺乏适当衡量这种不变性的一般方法。在本文中，我们提出了一个严格和系统的方法来量化任何分类器的几何变换的不变性。我们的主要想法是将评估分类器不变性的问题作为沿变换图像流形的计算。我们提出了Manitest方法，建立在有效的快速前进算法上来计算分类器的不变性。我们的新方法特别量化了从数据中学习不变性的数据增强的重要性，以及具有深度的卷积神经网络的不变性。我们可以预见，所提出的用于测量大量几何变换和任意分类器的不变性的通用工具将具有许多用于基于不变性评估和比较分类器的应用，并有助于改善现有分类器的不变性。

##### URL
[https://arxiv.org/abs/1507.06535](https://arxiv.org/abs/1507.06535)

##### PDF
[https://arxiv.org/pdf/1507.06535](https://arxiv.org/pdf/1507.06535)

