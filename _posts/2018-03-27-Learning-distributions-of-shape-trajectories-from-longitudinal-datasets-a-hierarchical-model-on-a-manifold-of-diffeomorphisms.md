---
layout: post
title: "Learning distributions of shape trajectories from longitudinal datasets: a hierarchical model on a manifold of diffeomorphisms"
date: 2018-03-27 15:03:51
categories: arXiv_CV
tags: arXiv_CV
author: Alexandre Bône, Olivier Colliot, Stanley Durrleman
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a method to learn a distribution of shape trajectories from longitudinal data, i.e. the collection of individual objects repeatedly observed at multiple time-points. The method allows to compute an average spatiotemporal trajectory of shape changes at the group level, and the individual variations of this trajectory both in terms of geometry and time dynamics. First, we formulate a non-linear mixed-effects statistical model as the combination of a generic statistical model for manifold-valued longitudinal data, a deformation model defining shape trajectories via the action of a finite-dimensional set of diffeomorphisms with a manifold structure, and an efficient numerical scheme to compute parallel transport on this manifold. Second, we introduce a MCMC-SAEM algorithm with a specific approach to shape sampling, an adaptive scheme for proposal variances, and a log-likelihood tempering strategy to estimate our model. Third, we validate our algorithm on 2D simulated data, and then estimate a scenario of alteration of the shape of the hippocampus 3D brain structure during the course of Alzheimer's disease. The method shows for instance that hippocampal atrophy progresses more quickly in female subjects, and occurs earlier in APOE4 mutation carriers. We finally illustrate the potential of our method for classifying pathological trajectories versus normal ageing.

##### Abstract (translated by Google)
我们提出了一种从纵向数据学习形状轨迹分布的方法，即在多个时间点重复观察单个物体的集合。该方法允许计算群体水平上形状变化的平均时空轨迹，以及该轨迹在几何和时间动态方面的个体变化。首先，我们制定了一个非线性混合效应统计模型作为流形值纵向数据的通用统计模型的组合，一个变形模型通过有限维微分同构与流形结构的作用定义形状轨迹，和一个有效的数值方案来计算这个流形上的平行运输。其次，我们引入一种MCMC-SAEM算法，采用特定的方法来形成抽样，提出方案的自适应方案，以及估计我们模型的对数似然回火策略。第三，我们验证了我们的2D模拟数据算法，然后估计了阿尔茨海默病过程中海马3D脑结构形状改变的情况。该方法显示，例如海马萎缩在女性受试者中进展更快，并且在APOE4突变携带者中出现得更早。我们最后说明了我们的方法分类病理轨迹与正常老化的潜力。

##### URL
[https://arxiv.org/abs/1803.10119](https://arxiv.org/abs/1803.10119)

##### PDF
[https://arxiv.org/pdf/1803.10119](https://arxiv.org/pdf/1803.10119)

