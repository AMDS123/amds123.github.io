---
layout: post
title: "Continuous 3D Label Stereo Matching using Local Expansion Moves"
date: 2017-10-17 10:31:50
categories: arXiv_CV
tags: arXiv_CV Regularization
author: Tatsunori Taniai, Yasuyuki Matsushita, Yoichi Sato, Takeshi Naemura
mathjax: true
---

* content
{:toc}

##### Abstract
We present an accurate stereo matching method using local expansion moves based on graph cuts. This new move-making scheme is used to efficiently infer per-pixel 3D plane labels on a pairwise Markov random field (MRF) that effectively combines recently proposed slanted patch matching and curvature regularization terms. The local expansion moves are presented as many alpha-expansions defined for small grid regions. The local expansion moves extend traditional expansion moves by two ways: localization and spatial propagation. By localization, we use different candidate alpha-labels according to the locations of local alpha-expansions. By spatial propagation, we design our local alpha-expansions to propagate currently assigned labels for nearby regions. With this localization and spatial propagation, our method can efficiently infer MRF models with a continuous label space using randomized search. Our method has several advantages over previous approaches that are based on fusion moves or belief propagation; it produces submodular moves deriving a subproblem optimality; it helps find good, smooth, piecewise linear disparity maps; it is suitable for parallelization; it can use cost-volume filtering techniques for accelerating the matching cost computations. Even using a simple pairwise MRF, our method is shown to have best performance in the Middlebury stereo benchmark V2 and V3.

##### Abstract (translated by Google)
我们提出一个精确的立体匹配方法，使用基于图切的局部展开移动。这种新的移动方案被用来有效地结合最近提出的倾斜斑块匹配和曲率正则化项来有效地结合成对马尔可夫随机场（MRF）上的每像素3D平面标签。本地扩展移动被呈现为为小网格区域定义的许多α扩展。本地扩张动作通过两种方式扩展了传统的扩张动作：本地化和空间传播。通过本地化，我们根据本地alpha扩展的位置使用不同的候选alpha标签。通过空间传播，我们设计我们的本地alpha扩展来传播当前为附近区域分配的标签。通过这种定位和空间传播，我们的方法可以使用随机搜索有效地推断具有连续标签空间的MRF模型。我们的方法比以前的融合移动或信念传播的方法有几个优点;它产生子模块运动导出子问题的最优性;它有助于找到好的，平滑的，分段的线性视差图;它适合并行化;它可以使用成本卷过滤技术来加速匹配成本计算。即使使用简单的成对MRF，我们的方法在Middlebury立体声基准V2和V3中也表现出最佳性能。

##### URL
[https://arxiv.org/abs/1603.08328](https://arxiv.org/abs/1603.08328)

##### PDF
[https://arxiv.org/pdf/1603.08328](https://arxiv.org/pdf/1603.08328)

