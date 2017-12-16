---
layout: post
title: "Unbiased Shape Compactness for Segmentation"
date: 2017-05-17 00:49:38
categories: arXiv_CV
tags: arXiv_CV Regularization Sparse Segmentation Optimization
author: Jose Dolz, Ismail Ben Ayed, Christian Desrosiers
mathjax: true
---

* content
{:toc}

##### Abstract
We propose to constrain segmentation functionals with a dimensionless, unbiased and position-independent shape compactness prior, which we solve efficiently with an alternating direction method of multipliers (ADMM). Involving a squared sum of pairwise potentials, our prior results in a challenging high-order optimization problem, which involves dense (fully connected) graphs. We split the problem into a sequence of easier sub-problems, each performed efficiently at each iteration: (i) a sparse-matrix inversion based on Woodbury identity, (ii) a closed-form solution of a cubic equation and (iii) a graph-cut update of a sub-modular pairwise sub-problem with a sparse graph. We deploy our prior in an energy minimization, in conjunction with a supervised classifier term based on CNNs and standard regularization constraints. We demonstrate the usefulness of our energy in several medical applications. In particular, we report comprehensive evaluations of our fully automated algorithm over 40 subjects, showing a competitive performance for the challenging task of abdominal aorta segmentation in MRI.

##### Abstract (translated by Google)
我们提出用无量纲的，无偏的和位置无关的形状紧致先验来约束分割函数，而我们用交替方向的乘法器（ADMM）来有效地解决这个问题。涉及平方和的潜在成分，我们的先前的结果是一个具有挑战性的高阶优化问题，其涉及密集（完全连接）的图。我们将问题分解成一系列更简单的子问题，每个问题在每次迭代中都有效地执行：（i）基于伍德伯里（Woodbury）身份的稀疏矩阵求逆，（ii）三次方程的封闭形式解，以及（iii）用稀疏图形进行子模块化成对子问题的图形切割更新。我们在能量最小化的基础上，结合基于CNN和标准正则化约束的监督分类器来部署我们的先验。我们证明了我们的能量在几个医疗应用中的有用性。特别是，我们报告全面评估我们的全自动算法超过40个科目，显示出一个具有挑战性的任务腹部主动脉分割磁共振成像的竞争力的表现。

##### URL
[https://arxiv.org/abs/1704.08908](https://arxiv.org/abs/1704.08908)

##### PDF
[https://arxiv.org/pdf/1704.08908](https://arxiv.org/pdf/1704.08908)

