---
layout: post
title: "Multi-Band Image Fusion Based on Spectral Unmixing"
date: 2016-03-29 10:54:21
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Qi Wei, Jose Bioucas-Dias, Nicolas Dobigeon, Jean-Yves Tourneret, Marcus Chen, Simon Godsill
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a multi-band image fusion algorithm based on unsupervised spectral unmixing for combining a high-spatial low-spectral resolution image and a low-spatial high-spectral resolution image. The widely used linear observation model (with additive Gaussian noise) is combined with the linear spectral mixture model to form the likelihoods of the observations. The non-negativity and sum-to-one constraints resulting from the intrinsic physical properties of the abundances are introduced as prior information to regularize this ill-posed problem. The joint fusion and unmixing problem is then formulated as maximizing the joint posterior distribution with respect to the endmember signatures and abundance maps, This optimization problem is attacked with an alternating optimization strategy. The two resulting sub-problems are convex and are solved efficiently using the alternating direction method of multipliers. Experiments are conducted for both synthetic and semi-real data. Simulation results show that the proposed unmixing based fusion scheme improves both the abundance and endmember estimation comparing with the state-of-the-art joint fusion and unmixing algorithms.

##### Abstract (translated by Google)
本文提出了一种基于无监督光谱分解的多波段图像融合算法，将高分辨率低分辨率图像和低分辨率高分辨率图像相结合。将广泛使用的线性观测模型（具有加性高斯噪声）与线性光谱混合模型组合以形成观测的可能性。引入丰度内在物理性​​质所导致的非负性和一对一约束作为事先信息来规范这个不适当的问题。然后将联合融合解混问题表示为相对于端成员签名和丰度图最大化联合后验分布。该优化问题受到交替优化策略的攻击。由此产生的两个子问题是凸的，并且使用乘法器的交替方向方法被有效地解决。对合成和半真实数据进行实验。仿真结果表明，与现有的联合融合和分解算法相比，基于分解的融合方案改善了丰度和端元估计。

##### URL
[https://arxiv.org/abs/1603.08720](https://arxiv.org/abs/1603.08720)

##### PDF
[https://arxiv.org/pdf/1603.08720](https://arxiv.org/pdf/1603.08720)

