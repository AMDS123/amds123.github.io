---
layout: post
title: "Volumetric Bias in Segmentation and Reconstruction: Secrets and Solutions"
date: 2015-05-01 17:01:37
categories: arXiv_CV
tags: arXiv_CV Segmentation Optimization
author: Yuri Boykov, Hossam Isack, Carl Olsson, Ismail Ben Ayed
mathjax: true
---

* content
{:toc}

##### Abstract
Many standard optimization methods for segmentation and reconstruction compute ML model estimates for appearance or geometry of segments, e.g. Zhu-Yuille 1996, Torr 1998, Chan-Vese 2001, GrabCut 2004, Delong et al. 2012. We observe that the standard likelihood term in these formulations corresponds to a generalized probabilistic K-means energy. In learning it is well known that this energy has a strong bias to clusters of equal size, which can be expressed as a penalty for KL divergence from a uniform distribution of cardinalities. However, this volumetric bias has been mostly ignored in computer vision. We demonstrate significant artifacts in standard segmentation and reconstruction methods due to this bias. Moreover, we propose binary and multi-label optimization techniques that either (a) remove this bias or (b) replace it by a KL divergence term for any given target volume distribution. Our general ideas apply to many continuous or discrete energy formulations in segmentation, stereo, and other reconstruction problems.

##### Abstract (translated by Google)
用于分割和重建的许多标准优化方法计算分段的外观或几何的ML模型估计，例如， Zhu-Yuille 1996，Torr 1998，Chan-Vese 2001，GrabCut 2004，Delong et al。我们观察到这些公式中的标准似然项对应于广义概率K均值能量。在学习中，众所周知，这种能量对于相同大小的群集具有强烈的偏见，这可以表示为对KL基于统一的基数分布的散度的惩罚。但是，这种体积偏差在计算机视觉中大多被忽视。由于这种偏见，我们在标准分割和重建方法中证明了显着的伪像。此外，我们提出了二元和多标签优化技术，要么（一）消除这种偏见或（b）任何给定的目标量分布KL替代项取代它。我们的一般想法适用于分段，立体声和其他重建问题中的许多连续或离散能量公式。

##### URL
[https://arxiv.org/abs/1505.00218](https://arxiv.org/abs/1505.00218)

##### PDF
[https://arxiv.org/pdf/1505.00218](https://arxiv.org/pdf/1505.00218)

