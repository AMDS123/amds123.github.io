---
layout: post
title: "Deformable Registration through Learning of Context-Specific Metric Aggregation"
date: 2017-07-19 19:06:38
categories: arXiv_CV
tags: arXiv_CV Weakly_Supervised
author: Enzo Ferrante, Puneet K Dokania, Rafael Marini, Nikos Paragios
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel weakly supervised discriminative algorithm for learning context specific registration metrics as a linear combination of conventional similarity measures. Conventional metrics have been extensively used over the past two decades and therefore both their strengths and limitations are known. The challenge is to find the optimal relative weighting (or parameters) of different metrics forming the similarity measure of the registration algorithm. Hand-tuning these parameters would result in sub optimal solutions and quickly become infeasible as the number of metrics increases. Furthermore, such hand-crafted combination can only happen at global scale (entire volume) and therefore will not be able to account for the different tissue properties. We propose a learning algorithm for estimating these parameters locally, conditioned to the data semantic classes. The objective function of our formulation is a special case of non-convex function, difference of convex function, which we optimize using the concave convex procedure. As a proof of concept, we show the impact of our approach on three challenging datasets for different anatomical structures and modalities.

##### Abstract (translated by Google)
我们提出了一种新颖的弱监督判别式算法，用于学习上下文特定的注册度量作为传统相似性度量的线性组合。传统指标在过去的二十年中被广泛使用，因此它们的优势和局限性都是已知的。面临的挑战是找到构成注册算法的相似性度量的不同度量的最佳相对加权（或参数）。手动调整这些参数会导致次最佳解决方案，并随着指标数量的增加而迅速变得不可行。此外，这种手工制作的组合只能在全球范围内（整个体积）发生，因此将不能解释不同的组织特性。我们提出了一个学习算法来估计这些参数在本地，条件的数据语义类。我们的公式的目标函数是凸函数的非凸函数的特例，我们用凹凸程序进行优化。作为一个概念证明，我们展示了我们的方法对三个具有挑战性的数据集的不同解剖结构和形式的影响。

##### URL
[https://arxiv.org/abs/1707.06263](https://arxiv.org/abs/1707.06263)

##### PDF
[https://arxiv.org/pdf/1707.06263](https://arxiv.org/pdf/1707.06263)

