---
layout: post
title: "Deterministic Hypothesis Generation for Robust Fitting of Multiple Structures"
date: 2018-07-25 01:28:28
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Kwang Hee Lee, Chanki Yu, Sang Wook Lee
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel algorithm for generating robust and consistent hypotheses for multiple-structure model fitting. Most of the existing methods utilize random sampling which produce varying results especially when outlier ratio is high. For a structure where a model is fitted, the inliers of other structures are regarded as outliers when multiple structures are present. Global optimization has recently been investigated to provide stable and unique solutions, but the computational cost of the algorithms is prohibitively high for most image data with reasonable sizes. The algorithm presented in this paper uses a maximum feasible subsystem (MaxFS) algorithm to generate consistent initial hypotheses only from partial datasets in spatially overlapping local image regions. Our assumption is that each genuine structure will exist as a dominant structure in at least one of the local regions. To refine initial hypotheses estimated from partial datasets and to remove residual tolerance dependency of the MaxFS algorithm, iterative re-weighted L1 (IRL1) minimization is performed for all the image data. Initial weights of IRL1 framework are determined from the initial hypotheses generated in local regions. Our approach is significantly more efficient than those that use only global optimization for all the image data. Experimental results demonstrate that the presented method can generate more reliable and consistent hypotheses than random-sampling methods for estimating single and multiple structures from data with a large amount of outliers. We clearly expose the influence of algorithm parameter settings on the results in our experiments.

##### Abstract (translated by Google)
我们提出了一种新的算法，用于生成多结构模型拟合的鲁棒和一致的假设。大多数现有方法利用随机采样，其产生不同的结果，尤其是当异常值比高时。对于安装模型的结构，当存在多个结构时，其他结构的内点被视为异常值。最近已经研究了全局优化以提供稳定且独特的解决方案，但是对于具有合理尺寸的大多数图像数据，算法的计算成本非常高。本文提出的算法使用最大可行子系统（MaxFS）算法，仅从空间重叠的局部图像区域中的部分数据集生成一致的初始假设。我们的假设是，每个真正的结构都将作为至少一个本地区域的主导结构存在。为了细化从部分数据集估计的初始假设并去除MaxFS算法的残余容差依赖性，对所有图像数据执行迭代重新加权L1（IRL1）最小化。 IRL1框架的初始权重由当地区域产生的初始假设确定。我们的方法比仅对所有图像数据使用全局优化的方法更有效。实验结果表明，所提出的方法可以产生比随机抽样方法更可靠和一致的假设，用于从具有大量异常值的数据估计单个和多个结构。我们清楚地揭示了算法参数设置对我们实验结果的影响。

##### URL
[http://arxiv.org/abs/1807.09408](http://arxiv.org/abs/1807.09408)

##### PDF
[http://arxiv.org/pdf/1807.09408](http://arxiv.org/pdf/1807.09408)

