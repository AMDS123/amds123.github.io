---
layout: post
title: "Model-free Consensus Maximization for Non-Rigid Shapes"
date: 2018-07-05 12:34:40
categories: arXiv_CV
tags: arXiv_CV
author: Thomas Probst, Ajad Chhatkuli, Danda Pani Paudel, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
Many computer vision methods rely on consensus maximization to relate measurements containing outliers with a reliable transformation model. In the context of matching rigid shapes, this is typically done using Random Sampling and Consensus (RANSAC) to estimate an analytical model that agrees with the largest number of measurements, which make the inliers. However, such models are either not available or too complex for non-rigid shapes. In this paper, we formulate the model-free consensus maximization problem as an Integer Program in a graph using 'rules' on measurements. We then provide a method to solve such a formulation optimally using the Branch and Bound (BnB) paradigm. In the context of non-rigid shapes, we apply the method to filter out outlier 3D correspondences and achieve performance superior to the state-of-the-art. Our method works with outlier ratio as high as 80%. We further derive a similar formulation for 3D template to image correspondences. Our approach achieves similar or better performance compared to the state-of-the-art.

##### Abstract (translated by Google)
许多计算机视觉方法依赖于共识最大化来将包含异常值的测量与可靠的变换模型相关联。在匹配刚性形状的情况下，这通常使用随机抽样和共识（RANSAC）来估计与最大数量的测量结果一致的分析模型，该模型产生内点。然而，这些模型要么不可用，要么对于非刚性形状来说太复杂。在本文中，我们使用测量的“规则”在图表中将无模型共识最大化问题表示为整数程序。然后，我们提供了一种使用分支定界（BnB）范例最佳地求解这种公式的方法。在非刚性形状的背景下，我们应用该方法来过滤掉异常的3D对应并实现优于现有技术的性能。我们的方法适用于异常值比率高达80％。我们进一步推导出类似的3D模板到图像对应的公式。与最先进的技术相比，我们的方法实现了类似或更好的性能。

##### URL
[http://arxiv.org/abs/1807.01963](http://arxiv.org/abs/1807.01963)

##### PDF
[http://arxiv.org/pdf/1807.01963](http://arxiv.org/pdf/1807.01963)

