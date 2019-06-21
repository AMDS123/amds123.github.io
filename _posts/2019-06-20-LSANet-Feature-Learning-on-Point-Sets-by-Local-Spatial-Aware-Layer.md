---
layout: post
title: "LSANet: Feature Learning on Point Sets by Local Spatial Aware Layer"
date: 2019-06-20 12:07:08
categories: arXiv_CV
tags: arXiv_CV Relation
author: Lin-Zhuo Chen, Xuan-Yi Li, Deng-Ping Fan, Kai Wang, Shao-Ping Lu, Ming-Ming Cheng
mathjax: true
---

* content
{:toc}

##### Abstract
Directly learning features from the point cloud has become an active research direction in 3D understanding. Existing learning-based methods usually construct local regions from the point cloud and extract the corresponding features. However, most of these processes do not adequately take the spatial distribution of the point cloud into account, limiting the ability to perceive fine-grained patterns. We design a novel Local Spatial Aware (LSA) layer, which can learn to generate Spatial Distribution Weights (SDWs) hierarchically based on the spatial relationship in local region for spatial independent operations, to establish the relationship between these operations and spatial distribution, thus capturing the local geometric structure sensitively.We further propose the LSANet, which is based on LSA layer, aggregating the spatial information with associated features in each layer of the network better in network design.The experiments show that our LSANet can achieve on par or better performance than the state-of-the-art methods when evaluating on the challenging benchmark datasets. For example, our LSANet can achieve 93.2% accuracy on ModelNet40 dataset using only 1024 points, significantly higher than other methods under the same conditions. The source code is available at https://github.com/LinZhuoChen/LSANet.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.05442](http://arxiv.org/abs/1905.05442)

##### PDF
[http://arxiv.org/pdf/1905.05442](http://arxiv.org/pdf/1905.05442)

