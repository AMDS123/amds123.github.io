---
layout: post
title: "A Framework for Dynamic Image Sampling Based on Supervised Learning"
date: 2017-03-14 18:36:16
categories: arXiv_CV
tags: arXiv_CV Sparse
author: G. M. Dilshan P. Godaliyadda, Dong Hye Ye, Michael D.Uchic, Michael A. Groeber, Gregery T. Buzzard, Charles A. Bouman
mathjax: true
---

* content
{:toc}

##### Abstract
Sparse sampling schemes have the potential to dramatically reduce image acquisition time while simultaneously reducing radiation damage to samples. However, for a sparse sampling scheme to be useful it is important that we are able to reconstruct the underlying object with sufficient clarity using the sparse measurements. In dynamic sampling, each new measurement location is selected based on information obtained from previous measurements. Therefore, dynamic sampling schemes have the potential to dramatically reduce the number of measurements needed for high fidelity reconstructions. However, most existing dynamic sampling methods for point-wise measurement acquisition tend to be computationally expensive and are therefore too slow for practical applications. In this paper, we present a framework for dynamic sampling based on machine learning techniques, which we call a supervised learning approach for dynamic sampling (SLADS). In each step of SLADS, the objective is to find the pixel that maximizes the expected reduction in distortion (ERD) given previous measurements. SLADS is fast because we use a simple regression function to compute the ERD, and it is accurate because the regression function is trained using data sets that are representative of the specific application. In addition, we introduce a method to terminate dynamic sampling at a desired level of distortion, and we extended the SLADS methodology to sample groups of pixels at each step. Finally, we present results on computationally-generated synthetic data and experimentally-collected data to demonstrate a dramatic improvement over state-of-the-art static sampling methods.

##### Abstract (translated by Google)
稀疏采样方案有可能显着缩短图像采集时间，同时减少对样本的辐射损伤。然而，为了使稀疏采样方案有用，重要的是我们能够使用稀疏度量以足够的清晰度重建潜在的对象。在动态采样中，每个新的测量位置都是根据之前测量得到的信息来选择的。因此，动态采样方案有可能显着减少高保真度重建所需的测量次数。然而，用于逐点测量采集的大多数现有的动态采样方法往往在计算上是昂贵的，因此在实际应用中太慢。在本文中，我们提出了一个基于机器学习技术的动态采样框架，我们称之为动态采样（SLADS）的监督学习方法。在SLADS的每个步骤中，目标是找到在先前的测量中最大化预期的失真减少（ERD）的像素。 SLADS速度很快，因为我们使用一个简单的回归函数来计算ERD，并且它是准确的，因为回归函数是使用代表具体应用的数据集来训练的。另外，我们介绍了一种终止所需失真水平的动态采样的方法，并且我们将SLADS方法扩展到每一步的像素采样组。最后，我们提供计算机生成的合成数据和实验收集的数据的结果，以证明相对于最先进的静态采样方法的显着改进。

##### URL
[https://arxiv.org/abs/1703.04653](https://arxiv.org/abs/1703.04653)

##### PDF
[https://arxiv.org/pdf/1703.04653](https://arxiv.org/pdf/1703.04653)

