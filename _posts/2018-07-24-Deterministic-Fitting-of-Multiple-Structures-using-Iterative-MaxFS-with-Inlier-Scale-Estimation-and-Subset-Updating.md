---
layout: post
title: "Deterministic Fitting of Multiple Structures using Iterative MaxFS with Inlier Scale Estimation and Subset Updating"
date: 2018-07-24 16:16:41
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Kwang Hee Lee, Sang Wook Lee
mathjax: true
---

* content
{:toc}

##### Abstract
We present an efficient deterministic hypothesis generation algorithm for robust fitting of multiple structures based on the maximum feasible subsystem (MaxFS) framework. Despite its advantage, a global optimization method such as MaxFS has two main limitations for geometric model fitting. First, its performance is much influenced by the user-specified inlier scale. Second, it is computationally inefficient for large data. The presented MaxFS-based algorithm iteratively estimates model parameters and inlier scale and also overcomes the second limitation by reducing data for the MaxFS problem. Further it generates hypotheses only with top-n ranked subsets based on matching scores and data fitting residuals. This reduction of data for the MaxFS problem makes the algorithm computationally realistic. Our method, called iterative MaxFS with inlier scale estimation and subset updating (IMaxFS-ISE-SU) in this paper, performs hypothesis generation and fitting alternately until all of true structures are found. The IMaxFS-ISE-SU algorithm generates substantially more reliable hypotheses than random sampling-based methods especially as (pseudo-)outlier ratios increase. Experimental results demonstrate that our method can generate more reliable and consistent hypotheses than random sampling-based methods for estimating multiple structures from data with many outliers.

##### Abstract (translated by Google)
我们提出了一种有效的确定性假设生成算法，用于基于最大可行子系统（MaxFS）框架对多个结构进行鲁棒拟合。尽管有其优点，但MaxFS等全局优化方法对几何模型拟合有两个主要限制。首先，它的性能受用户指定的内部规模的影响很大。其次，对于大数据来说，它在计算上是低效的。所提出的基于MaxFS的算法迭代地估计模型参数和内部规模，并且还通过减少MaxFS问题的数据来克服第二限制。此外，它仅基于匹配分数和数据拟合残差，仅对排名前n的子集生成假设。 MaxFS问题的数据减少使得算法在计算上是现实的。我们的方法，在本文中称为具有inlier尺度估计和子集更新的迭代MaxFS（IMaxFS-ISE-SU），交替执行假设生成和拟合，直到找到所有真实结构。 IMaxFS-ISE-SU算法比基于随机采样的方法产生更可靠的假设，特别是随着（伪）异常值比率的增加。实验结果表明，我们的方法可以产生比基于随机抽样的方法更可靠和一致的假设，用于从具有许多异常值的数据估计多个结构。

##### URL
[https://arxiv.org/abs/1807.09210](https://arxiv.org/abs/1807.09210)

##### PDF
[https://arxiv.org/pdf/1807.09210](https://arxiv.org/pdf/1807.09210)

