---
layout: post
title: "Data-Free/Data-Sparse Softmax Parameter Estimation with Structured Class Geometries"
date: 2018-06-03 02:03:32
categories: arXiv_CV
tags: arXiv_CV Sparse Optimization Classification
author: Nisar Ahmed
mathjax: true
---

* content
{:toc}

##### Abstract
This note considers softmax parameter estimation when little/no labeled training data is available, but a priori information about the relative geometry of class label log-odds boundaries is available. It is shown that `data-free' softmax model synthesis corresponds to solving a linear system of parameter equations, wherein desired dominant class log-odds boundaries are encoded via convex polytopes that decompose the input feature space. When solvable, the linear equations yield closed-form softmax parameter solution families using class boundary polytope specifications only. This allows softmax parameter learning to be implemented without expensive brute force data sampling and numerical optimization. The linear equations can also be adapted to constrained maximum likelihood estimation in data-sparse settings. Since solutions may also fail to exist for the linear parameter equations derived from certain polytope specifications, it is thus also shown that there exist probabilistic classification problems over m convexly separable classes for which the log-odds boundaries cannot be learned using an m-class softmax model.

##### Abstract (translated by Google)
本小节考虑了softmax参数估计，当少量/没有标记的训练数据可用时，但可以获得关于类别标签日志赔率边界的相关几何的先验信息。结果表明，“无数据”softmax模型综合对应于求解参数方程的线性系统，其中期望的主导类对数边界通过分解输入特征空间的凸多面体编码。当可解时，线性方程式仅产生使用类边界多面体规范的闭式softmax参数解系列。这允许softmax参数学习在没有昂贵的强力数据采样和数值优化的情况下实施。线性方程也可以适用于数据稀疏设置中的约束最大似然估计。由于对于从某些多面体规范导出的线性参数方程也可能不存在解，因此也表明存在m个凸可分类的概率分类问题，其中使用m级softmax无法学习对数极限边界模型。

##### URL
[http://arxiv.org/abs/1806.00728](http://arxiv.org/abs/1806.00728)

##### PDF
[http://arxiv.org/pdf/1806.00728](http://arxiv.org/pdf/1806.00728)

