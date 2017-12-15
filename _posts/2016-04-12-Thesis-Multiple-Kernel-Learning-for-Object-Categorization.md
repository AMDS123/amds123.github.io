---
layout: post
title: "Thesis: Multiple Kernel Learning for Object Categorization"
date: 2016-04-12 04:56:24
categories: arXiv_CV
tags: arXiv_CV Regularization Classification Recognition
author: Dinesh Govindaraj
mathjax: true
---

* content
{:toc}

##### Abstract
Object Categorization is a challenging problem, especially when the images have clutter background, occlusions or different lighting conditions. In the past, many descriptors have been proposed which aid object categorization even in such adverse conditions. Each descriptor has its own merits and de-merits. Some descriptors are invariant to transformations while the others are more discriminative. Past research has shown that, employing multiple descriptors rather than any single descriptor leads to better recognition. The problem of learning the optimal combination of the available descriptors for a particular classification task is studied. Multiple Kernel Learning (MKL) framework has been developed for learning an optimal combination of descriptors for object categorization. Existing MKL formulations often employ block l-1 norm regularization which is equivalent to selecting a single kernel from a library of kernels. Since essentially a single descriptor is selected, the existing formulations maybe sub- optimal for object categorization. A MKL formulation based on block l-infinity norm regularization has been developed, which chooses an optimal combination of kernels as opposed to selecting a single kernel. A Composite Multiple Kernel Learning(CKL) formulation based on mixed l-infinity and l-1 norm regularization has been developed. These formulations end in Second Order Cone Programs(SOCP). Other efficient alter- native algorithms for these formulation have been implemented. Empirical results on benchmark datasets show significant improvement using these new MKL formulations.

##### Abstract (translated by Google)
对象分类是一个具有挑战性的问题，特别是当图像具有杂乱背景，遮挡或不同的光照条件时。过去，许多描述符已经被提出，即使在这样的不利条件下也能帮助对象分类。每个描述符都有其优点和缺点。一些描述符对于转换是不变的，而其他的则更具有区别性。过去的研究表明，使用多个描述符而不是任何一个描述符会导致更好的识别。研究了针对特定分类任务学习可用描述符的最优组合的问题。已经开发了多内核学习（MKL）框架来学习用于对象分类的描述符的最佳组合。现有的MKL公式通常使用块1-1范数正则化，这相当于从一个内核库中选择一个单一的内核。由于基本上选择了单个描述符，所以现有配方可能不适合对象分类。已经开发了基于块l-无穷范数正则化的MKL公式，该公式选择内核的最优组合，而不是选择单个内核。已经开发了基于混合l-无限和l-1范数正则化的复合多核学习（CKL）公式。这些配方以二阶锥形程序（SOCP）结束。其他有效的替代算法已经被实现。基准数据集的实证结果显示使用这些新的MKL配方显着改善。

##### URL
[https://arxiv.org/abs/1604.03247](https://arxiv.org/abs/1604.03247)

##### PDF
[https://arxiv.org/pdf/1604.03247](https://arxiv.org/pdf/1604.03247)

