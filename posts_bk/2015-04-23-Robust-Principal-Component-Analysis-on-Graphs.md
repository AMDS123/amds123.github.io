---
layout: post
title: "Robust Principal Component Analysis on Graphs"
date: 2015-04-23 12:39:40
categories: arXiv_CV
tags: arXiv_CV Regularization Sparse Optimization
author: Nauman Shahid, Vassilis Kalofolias, Xavier Bresson, Michael Bronstein, Pierre Vandergheynst
mathjax: true
---

* content
{:toc}

##### Abstract
Principal Component Analysis (PCA) is the most widely used tool for linear dimensionality reduction and clustering. Still it is highly sensitive to outliers and does not scale well with respect to the number of data samples. Robust PCA solves the first issue with a sparse penalty term. The second issue can be handled with the matrix factorization model, which is however non-convex. Besides, PCA based clustering can also be enhanced by using a graph of data similarity. In this article, we introduce a new model called "Robust PCA on Graphs" which incorporates spectral graph regularization into the Robust PCA framework. Our proposed model benefits from 1) the robustness of principal components to occlusions and missing values, 2) enhanced low-rank recovery, 3) improved clustering property due to the graph smoothness assumption on the low-rank matrix, and 4) convexity of the resulting optimization problem. Extensive experiments on 8 benchmark, 3 video and 2 artificial datasets with corruptions clearly reveal that our model outperforms 10 other state-of-the-art models in its clustering and low-rank recovery tasks.

##### Abstract (translated by Google)
主成分分析（PCA）是线性降维和聚类中使用最广泛的工具。它仍然对异常值非常敏感，并且在数据采样数方面不能很好地扩展。稳健的PCA用一个稀疏的惩罚项解决了第一个问题。第二个问题可以用矩阵分解模型来处理，但是这是非凸的。此外，基于PCA的聚类也可以通过使用数据相似度图来增强。在这篇文章中，我们引入了一个名为“Robust PCA on Graphs”的新模型，该模型将频谱图正则化结合到Robust PCA框架中。我们提出的模型受益于：1）主成分对闭塞和缺失值的鲁棒性; 2）增强的低秩恢复; 3）由于低秩矩阵上的图平滑假设而改善的聚类性质;以及4）导致优化问题。在8个基准测试，3个视频和2个具有损坏的人造数据集上的大量实验清楚地表明，我们的模型在聚类和低级恢复任务中胜过了其他10个最先进的模型。

##### URL
[https://arxiv.org/abs/1504.06151](https://arxiv.org/abs/1504.06151)

##### PDF
[https://arxiv.org/pdf/1504.06151](https://arxiv.org/pdf/1504.06151)

