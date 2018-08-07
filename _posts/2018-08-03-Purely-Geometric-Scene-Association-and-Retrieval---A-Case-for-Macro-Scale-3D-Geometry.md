---
layout: post
title: "Purely Geometric Scene Association and Retrieval - A Case for Macro Scale 3D Geometry"
date: 2018-08-03 20:20:40
categories: arXiv_RO
tags: arXiv_RO Sparse Face Deep_Learning Relation
author: Rahul Sawhney, Fuxin Li, Henrik I. Christensen, Charles L. Isbell
mathjax: true
---

* content
{:toc}

##### Abstract
We address the problems of measuring geometric similarity between 3D scenes, represented through point clouds or range data frames, and associating them. Our approach leverages macro-scale 3D structural geometry - the relative configuration of arbitrary surfaces and relationships among structures that are potentially far apart. We express such discriminative information in a viewpoint-invariant feature space. These are subsequently encoded in a frame-level signature that can be utilized to measure geometric similarity. Such a characterization is robust to noise, incomplete and partially overlapping data besides viewpoint changes. We show how it can be employed to select a diverse set of data frames which have structurally similar content, and how to validate whether views with similar geometric content are from the same scene. The problem is formulated as one of general purpose retrieval from an unannotated, spatio-temporally unordered database. Empirical analysis indicates that the presented approach thoroughly outperforms baselines on depth / range data. Its depth-only performance is competitive with state-of-the-art approaches with RGB or RGB-D inputs, including ones based on deep learning. Experiments show retrieval performance to hold up well with much sparser databases, which is indicative of the approach's robustness. The approach generalized well - it did not require dataset specific training, and scaled up in our experiments. Finally, we also demonstrate how geometrically diverse selection of views can result in richer 3D reconstructions.

##### Abstract (translated by Google)
我们解决了测量3D场景之间几何相似性的问题，通过点云或范围数据帧表示，并将它们相关联。我们的方法利用宏观尺度的三维结构几何 - 任意曲面的相对配置以及可能相距很远的结构之间的关系。我们在视点不变特征空间中表达这种判别信息。随后将这些编码在帧级签名中，该签名可用于测量几何相似性。除了视点变化之外，这种表征对于噪声，不完整和部分重叠的数据是鲁棒的。我们展示了如何使用它来选择具有结构相似内容的各种数据帧，以及如何验证具有相似几何内容的视图是否来自同一场景。该问题被公式化为来自未注释的，时空无序数据库的通用检索。实证分析表明，所提出的方法完全优于深度/范围数据的基线。它的仅深度性能与具有RGB或RGB-D输入的最先进方法相比具有竞争力，包括基于深度学习的输入。实验表明，检索性能可以很好地保留在更稀疏的数据库中，这表明了该方法的稳健性。该方法概括良好 - 它不需要数据集特定的训练，并在我们的实验中扩大规模。最后，我们还演示了几何上多样化的视图选择如何能够实现更丰富的3D重建。

##### URL
[http://arxiv.org/abs/1808.01343](http://arxiv.org/abs/1808.01343)

##### PDF
[http://arxiv.org/pdf/1808.01343](http://arxiv.org/pdf/1808.01343)

