---
layout: post
title: "Geometric Scene Parsing with Hierarchical LSTM"
date: 2016-04-08 06:21:57
categories: arXiv_CV
tags: arXiv_CV Face RNN Prediction Relation
author: Zhanglin Peng, Ruimao Zhang, Xiaodan Liang, Xiaobai Liu, Liang Lin
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the problem of geometric scene parsing, i.e. simultaneously labeling geometric surfaces (e.g. sky, ground and vertical plane) and determining the interaction relations (e.g. layering, supporting, siding and affinity) between main regions. This problem is more challenging than the traditional semantic scene labeling, as recovering geometric structures necessarily requires the rich and diverse contextual information. To achieve these goals, we propose a novel recurrent neural network model, named Hierarchical Long Short-Term Memory (H-LSTM). It contains two coupled sub-networks: the Pixel LSTM (P-LSTM) and the Multi-scale Super-pixel LSTM (MS-LSTM) for handling the surface labeling and relation prediction, respectively. The two sub-networks provide complementary information to each other to exploit hierarchical scene contexts, and they are jointly optimized for boosting the performance. Our extensive experiments show that our model is capable of parsing scene geometric structures and outperforming several state-of-the-art methods by large margins. In addition, we show promising 3D reconstruction results from the still images based on the geometric parsing.

##### Abstract (translated by Google)
本文论述了几何场景解析的问题，即同时标记几何表面（例如天空，地面和垂直平面），并确定主要区域之间的相互作用关系（例如，分层，支撑，侧板和亲和性）。这个问题比传统的语义场景标注更具挑战性，因为恢复几何结构必然需要丰富多样的上下文信息。为了实现这些目标，我们提出了一种新型的递归神经网络模型，即H-LSTM（Hierarchical Long Short Term Memory）。它包含两个耦合子网络：分别用于处理表面标记和关系预测的像素LSTM（P-LSTM）和多尺度超像素LSTM（MS-LSTM）。这两个子网络互相提供互补信息以利用分层场景情境，并且它们被共同优化以提高性能。我们广泛的实验表明，我们的模型能够解析场景几何结构，并且大幅度地超越了几种最先进的方法。另外，基于几何解析的静止图像显示了有前途的三维重建结果。

##### URL
[https://arxiv.org/abs/1604.01931](https://arxiv.org/abs/1604.01931)

##### PDF
[https://arxiv.org/pdf/1604.01931](https://arxiv.org/pdf/1604.01931)

