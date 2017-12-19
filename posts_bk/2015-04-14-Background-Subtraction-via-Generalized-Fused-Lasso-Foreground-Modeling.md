---
layout: post
title: "Background Subtraction via Generalized Fused Lasso Foreground Modeling"
date: 2015-04-14 20:25:27
categories: arXiv_CV
tags: arXiv_CV Regularization Sparse Segmentation Optimization
author: Bo Xin, Yuan Tian, Yizhou Wang, Wen Gao
mathjax: true
---

* content
{:toc}

##### Abstract
Background Subtraction (BS) is one of the key steps in video analysis. Many background models have been proposed and achieved promising performance on public data sets. However, due to challenges such as illumination change, dynamic background etc. the resulted foreground segmentation often consists of holes as well as background noise. In this regard, we consider generalized fused lasso regularization to quest for intact structured foregrounds. Together with certain assumptions about the background, such as the low-rank assumption or the sparse-composition assumption (depending on whether pure background frames are provided), we formulate BS as a matrix decomposition problem using regularization terms for both the foreground and background matrices. Moreover, under the proposed formulation, the two generally distinctive background assumptions can be solved in a unified manner. The optimization was carried out via applying the augmented Lagrange multiplier (ALM) method in such a way that a fast parametric-flow algorithm is used for updating the foreground matrix. Experimental results on several popular BS data sets demonstrate the advantage of the proposed model compared to state-of-the-arts.

##### Abstract (translated by Google)
背景减法（BS）是视频分析的关键步骤之一。已经提出了许多背景模型，并在公共数据集上取得了有希望的性能。然而，由于光照变化，动态背景等的挑战，所产生的前景分割通常包括空洞以及背景噪声。在这方面，我们考虑广义融合的套索正则化来寻求完整的结构化前景。再加上一些关于背景的假设，比如低秩假设或稀疏组合假设（取决于是否提供了纯背景帧），我们将BS用前向和背景矩阵的正则化项表示为矩阵分解问题。而且，根据所提出的表述，可以统一地解决两个通常不同的背景假设。通过应用增广的拉格朗日乘子（ALM）方法进行优化，使得快速参数流算法用于更新前景矩阵。对几个流行的BS数据集的实验结果证明了与现有技术相比所提出的模型的优点。

##### URL
[https://arxiv.org/abs/1504.03707](https://arxiv.org/abs/1504.03707)

##### PDF
[https://arxiv.org/pdf/1504.03707](https://arxiv.org/pdf/1504.03707)

