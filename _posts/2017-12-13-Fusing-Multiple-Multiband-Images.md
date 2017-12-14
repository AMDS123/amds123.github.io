---
layout: post
title: "Fusing Multiple Multiband Images"
date: 2017-12-13 00:09:28
categories: arXiv_CV
tags: arXiv_CV Regularization Knowledge Optimization
author: Reza Arablouei
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the problem of fusing an arbitrary number of multiband, i.e., panchromatic, multispectral, or hyperspectral, images belonging to the same scene. We use the well-known forward observation and linear mixture models with Gaussian perturbations to formulate the maximum-likelihood estimator of the endmember abundance matrix of the fused image. We calculate the Fisher information matrix for this estimator and examine the conditions for the uniqueness of the estimator. We use a vector total-variation penalty term together with nonnegativity and sum-to-one constraints on the endmember abundances to regularize the derived maximum-likelihood estimation problem. The regularization facilitates exploiting the prior knowledge that natural images are mostly composed of piecewise smooth regions with limited abrupt changes, i.e., edges, as well as coping with potential ill-posedness of the fusion problem. We solve the resultant convex optimization problem using the alternating direction method of multipliers. We utilize the circular convolution theorem in conjunction with the fast Fourier transform to alleviate the computational complexity of the proposed algorithm. Experiments with multiband images constructed from real hyperspectral datasets reveal the superior performance of the proposed algorithm in comparison with the state-of-the-art algorithms, which need to be used in tandem to fuse more than two multiband images.

##### Abstract (translated by Google)
我们考虑融合任意数量的多频带，即属于同一场景的全色，多光谱或高光谱图像的问题。我们使用众所周知的具有高斯扰动的前向观测和线性混合模型来构造融合图像的端元丰度矩阵的最大似然估计。我们计算这个估计量的Fisher信息矩阵，并检验估计量唯一性的条件。我们使用矢量总变量惩罚项以及端元丰度的非负性和和一约束来规范导出的最大似然估计问题。正则化有利于利用先验知识，即自然图像主要由具有有限的突变（即边缘）的分段平滑区域组成，并且应对潜在的融合问题的不适宜性。我们使用乘法器的交替方向方法来解决由此产生的凸优化问题。我们利用循环卷积定理与快速傅里叶变换相结合来减轻所提算法的计算复杂度。实际的高光谱数据集构建的多波段图像实验表明，与现有技术相比，该算法具有优越的性能，需要两个以上的多波段图像进行融合。

##### URL
[http://arxiv.org/abs/1712.04575](http://arxiv.org/abs/1712.04575)

##### PDF
[http://arxiv.org/pdf/1712.04575](http://arxiv.org/pdf/1712.04575)

