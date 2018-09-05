---
layout: post
title: "Hierarchically Learned View-Invariant Representations for Cross-View Action Recognition"
date: 2018-09-03 01:31:05
categories: arXiv_CV
tags: arXiv_CV Sparse Action_Recognition Recognition
author: Yang Liu, Zhaoyang Lu, Jing Li, Tao Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Recognizing human actions from varied views is challenging due to huge appearance variations in different views. The key to this problem is to learn discriminant view-invariant representations generalizing well across views. In this paper, we address this problem by learning view-invariant representations hierarchically using a novel method, referred to as Joint Sparse Representation and Distribution Adaptation (JSRDA). To obtain robust and informative feature representations, we first incorporate a sample-affinity matrix into the marginalized stacked denoising Autoencoder (mSDA) to obtain shared features, which are then combined with the private features. In order to make the feature representations of videos across views transferable, we then learn a transferable dictionary pair simultaneously from pairs of videos taken at different views to encourage each action video across views to have the same sparse representation. However, the distribution difference across views still exists because a unified subspace where the sparse representations of one action across views are the same may not exist when the view difference is large. Therefore, we propose a novel unsupervised distribution adaptation method that learns a set of projections that project the source and target views data into respective low-dimensional subspaces where the marginal and conditional distribution differences are reduced simultaneously. Therefore, the finally learned feature representation is view-invariant and robust for substantial distribution difference across views even the view difference is large. Experimental results on four multiview datasets show that our approach outperforms the state-ofthe-art approaches.

##### Abstract (translated by Google)
由于不同观点的巨大外观变化，认识到来自不同观点的人类行为具有挑战性。这个问题的关键是学习在视图中很好地概括的判别式视图不变表示。在本文中，我们通过使用一种新颖的方法（称为联合稀疏表示和分布自适应（JSRDA））分层学习视图不变表示来解决这个问题。为了获得稳健且信息丰富的特征表示，我们首先将样本亲和度矩阵合并到边缘化堆叠去噪自动编码器（mSDA）中以获得共享特征，然后将其与私有特征组合。为了使视图中的视频的特征表示可以转移，我们然后从在不同视图处拍摄的视频对同时学习可转换的字典对，以鼓励跨视图的每个动作视频具有相同的稀疏表示。但是，跨视图的分布差异仍然存在，因为当视图差异很大时，可能不存在跨视图的一个动作的稀疏表示相同的统一子空间。因此，我们提出了一种新颖的无监督分布自适应方法，该方法学习一组投影，其将源和目标视图数据投影到相应的低维子空间中，其中边缘和条件分布差异被同时减小。因此，即使视图差异很大，最终学习的特征表示也是视图不变的并且对于跨视图的实质分布差异是鲁棒的。四个多视图数据集的实验结果表明，我们的方法优于最先进的方法。

##### URL
[http://arxiv.org/abs/1809.00421](http://arxiv.org/abs/1809.00421)

##### PDF
[http://arxiv.org/pdf/1809.00421](http://arxiv.org/pdf/1809.00421)

