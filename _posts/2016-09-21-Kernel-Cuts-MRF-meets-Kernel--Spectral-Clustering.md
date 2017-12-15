---
layout: post
title: "Kernel Cuts: MRF meets Kernel & Spectral Clustering"
date: 2016-09-21 03:41:06
categories: arXiv_CV
tags: arXiv_CV Regularization Segmentation Optimization
author: Meng Tang, Dmitrii Marin, Ismail Ben Ayed, Yuri Boykov
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new segmentation model combining common regularization energies, e.g. Markov Random Field (MRF) potentials, and standard pairwise clustering criteria like Normalized Cut (NC), average association (AA), etc. These clustering and regularization models are widely used in machine learning and computer vision, but they were not combined before due to significant differences in the corresponding optimization, e.g. spectral relaxation and combinatorial max-flow techniques. On the one hand, we show that many common applications using MRF segmentation energies can benefit from a high-order NC term, e.g. enforcing balanced clustering of arbitrary high-dimensional image features combining color, texture, location, depth, motion, etc. On the other hand, standard clustering applications can benefit from an inclusion of common pairwise or higher-order MRF constraints, e.g. edge alignment, bin-consistency, label cost, etc. To address joint energies like NC+MRF, we propose efficient Kernel Cut algorithms based on bound optimization. While focusing on graph cut and move-making techniques, our new unary (linear) kernel and spectral bound formulations for common pairwise clustering criteria allow to integrate them with any regularization functionals with existing discrete or continuous solvers.

##### Abstract (translated by Google)
我们提出了一种结合了普通正则化能量的新的分割模型，马尔科夫随机场（Markov Random Field，MRF）电位以及标准化切割（NC），平均关联（AA）等标准成对聚类标准。这些聚类和正则化模型广泛应用于机器学习和计算机视觉领域，在相应的优化方面有显着差异，例如谱弛豫和组合最大流技术。一方面，我们展示了许多使用MRF分割能量的常见应用可以从高阶NC项中受益，例如，执行结合颜色，纹理，位置，深度，运动等的任意高维图像特征的平衡聚类。另一方面，标准聚类应用可以受益于包含常见的成对或高阶MRF约束，例如，边缘对齐，一致性，标签成本等。为了解决NC + MRF等联合能量问题，提出了基于约束优化的高效Kernel Cut算法。在专注于图形切割和移动技术的同时，我们新的一元（线性）核和谱边界公式用于常见的成对聚类准则允许将它们与任何正则化函数与现有的离散或连续求解器集成。

##### URL
[https://arxiv.org/abs/1506.07439](https://arxiv.org/abs/1506.07439)

##### PDF
[https://arxiv.org/pdf/1506.07439](https://arxiv.org/pdf/1506.07439)

