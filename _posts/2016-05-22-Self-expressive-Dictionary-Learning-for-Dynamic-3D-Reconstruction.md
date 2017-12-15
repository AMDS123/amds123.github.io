---
layout: post
title: "Self-expressive Dictionary Learning for Dynamic 3D Reconstruction"
date: 2016-05-22 23:56:34
categories: arXiv_CV
tags: arXiv_CV Sparse Relation
author: Enliang Zheng, Dinghuang Ji, Enrique Dunn, Jan-Michael Frahm
mathjax: true
---

* content
{:toc}

##### Abstract
We target the problem of sparse 3D reconstruction of dynamic objects observed by multiple unsynchronized video cameras with unknown temporal overlap. To this end, we develop a framework to recover the unknown structure without sequencing information across video sequences. Our proposed compressed sensing framework poses the estimation of 3D structure as the problem of dictionary learning, where the dictionary is defined as an aggregation of the temporally varying 3D structures. Given the smooth motion of dynamic objects, we observe any element in the dictionary can be well approximated by a sparse linear combination of other elements in the same dictionary (i. e. self-expression). Moreover, the sparse coefficients describing a locally linear 3D structural interpolation reveal the local sequencing information. Our formulation optimizes a biconvex cost function that leverages a compressed sensing formulation and enforces both structural dependency coherence across video streams, as well as motion smoothness across estimates from common video sources. We further analyze the reconstructability of our approach under different capture scenarios, and its comparison and relation to existing methods. Experimental results on large amounts of synthetic data as well as real imagery demonstrate the effectiveness of our approach.

##### Abstract (translated by Google)
我们针对未知时间重叠的多个未同步摄像机所观察到的动态物体的稀疏三维重建问题。为此，我们开发了一个框架来恢复未知结构，而不需要在视频序列中排序信息。我们提出的压缩感知框架将三维结构的估计作为字典学习的问题，其中字典被定义为时间变化的三维结构的聚集。考虑到动态对象的平滑运动，我们观察到字典中的任何元素可以通过同一字典中的其他元素的稀疏线性组合（即，自我表达）很好地近似。此外，描述局部线性3D结构插值的稀疏系数揭示了局部测序信息。我们的配方优化了双凸面成本函数，该函数利用压缩感知公式，并加强视频流之间的结构依赖性一致性，以及来自常见视频源的估计的运动平滑度。我们进一步分析我们的方法在不同的捕捉场景下的可重构性，以及与现有方法的比较和关系。大量合成数据和实际图像的实验结果证明了我们方法的有效性。

##### URL
[https://arxiv.org/abs/1605.06863](https://arxiv.org/abs/1605.06863)

##### PDF
[https://arxiv.org/pdf/1605.06863](https://arxiv.org/pdf/1605.06863)

