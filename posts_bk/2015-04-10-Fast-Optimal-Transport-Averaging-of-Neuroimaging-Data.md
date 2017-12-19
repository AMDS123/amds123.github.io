---
layout: post
title: "Fast Optimal Transport Averaging of Neuroimaging Data"
date: 2015-04-10 01:47:02
categories: arXiv_CV
tags: arXiv_CV GAN Face Optimization
author: Alexandre Gramfort, Gabriel Peyré, Marco Cuturi
mathjax: true
---

* content
{:toc}

##### Abstract
Knowing how the Human brain is anatomically and functionally organized at the level of a group of healthy individuals or patients is the primary goal of neuroimaging research. Yet computing an average of brain imaging data defined over a voxel grid or a triangulation remains a challenge. Data are large, the geometry of the brain is complex and the between subjects variability leads to spatially or temporally non-overlapping effects of interest. To address the problem of variability, data are commonly smoothed before group linear averaging. In this work we build on ideas originally introduced by Kantorovich to propose a new algorithm that can average efficiently non-normalized data defined over arbitrary discrete domains using transportation metrics. We show how Kantorovich means can be linked to Wasserstein barycenters in order to take advantage of an entropic smoothing approach. It leads to a smooth convex optimization problem and an algorithm with strong convergence guarantees. We illustrate the versatility of this tool and its empirical behavior on functional neuroimaging data, functional MRI and magnetoencephalography (MEG) source estimates, defined on voxel grids and triangulations of the folded cortical surface.

##### Abstract (translated by Google)
了解人脑在解剖学和功能上是如何组织在一组健康个体或患者的水平是神经影像学研究的主要目标。然而，计算在体素网格或三角网格上定义的大脑成像数据的平均值仍然是一个挑战。数据很大，大脑的几何形状复杂，主体之间的变异性会导致空间或时间上不重叠的兴趣效应。为了解决可变性的问题，数据通常在群组线性平均之前被平滑。在这项工作中，我们基于Kantorovich最初提出的想法来提出一种新的算法，该算法可以使用运输指标有效地平均在任意离散域上定义的非标准化数据。我们展示了Kantorovich的意思是如何与Wasserstein重心联系，以便利用熵平滑方法。这导致了一个光滑的凸优化问题和一个具有强收敛保证的算法。我们举例说明了这种工具的多功能性及其在功能神经影像学数据，功能性MRI和脑磁图（MEG）源估计上的经验行为，定义在体素网格和折叠的皮质表面的三角形上。

##### URL
[https://arxiv.org/abs/1503.08596](https://arxiv.org/abs/1503.08596)

##### PDF
[https://arxiv.org/pdf/1503.08596](https://arxiv.org/pdf/1503.08596)

