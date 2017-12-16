---
layout: post
title: "Robust Depth-based Person Re-identification"
date: 2017-03-28 09:26:54
categories: arXiv_CV
tags: arXiv_CV Re-identification Person_Re-identification
author: Ancong Wu, Wei-Shi Zheng, Jianhuang Lai
mathjax: true
---

* content
{:toc}

##### Abstract
Person re-identification (re-id) aims to match people across non-overlapping camera views. So far the RGB-based appearance is widely used in most existing works. However, when people appeared in extreme illumination or changed clothes, the RGB appearance-based re-id methods tended to fail. To overcome this problem, we propose to exploit depth information to provide more invariant body shape and skeleton information regardless of illumination and color change. More specifically, we exploit depth voxel covariance descriptor and further propose a locally rotation invariant depth shape descriptor called Eigen-depth feature to describe pedestrian body shape. We prove that the distance between any two covariance matrices on the Riemannian manifold is equivalent to the Euclidean distance between the corresponding Eigen-depth features. Furthermore, we propose a kernelized implicit feature transfer scheme to estimate Eigen-depth feature implicitly from RGB image when depth information is not available. We find that combining the estimated depth features with RGB-based appearance features can sometimes help to better reduce visual ambiguities of appearance features caused by illumination and similar clothes. The effectiveness of our models was validated on publicly available depth pedestrian datasets as compared to related methods for person re-identification.

##### Abstract (translated by Google)
个人重新识别（re-id）旨在匹配非重叠摄像机视图的人员。到目前为止，基于RGB的外观在大多数现有的作品中被广泛使用。然而，当人们出现极度照明或更换衣服时，基于RGB外观的重新识别方法往往失败。为了克服这个问题，我们建议利用深度信息来提供更多不变的身体形状和骨架信息，而不管光照和颜色变化。更具体地说，我们利用深度体素协方差描述符，并进一步提出称为特征深度特征的局部旋转不变深度形状描述符来描述行人体形状。证明了黎曼流形上任意两个协方差矩阵之间的距离等于对应特征深度特征之间的欧几里德距离。此外，当深度信息不可用时，我们提出了一种核化的隐式特征转移方案来从RGB图像中隐式地估计特征深度特征。我们发现，将估计的深度特征与基于RGB的外观特征组合有时可以帮助更好地减少由照明和类似的衣服引起的外观特征的可视歧义。我们的模型的有效性在公开可用的深度人行数据集上与相关的人重新识别方法相比得到验证。

##### URL
[https://arxiv.org/abs/1703.09474](https://arxiv.org/abs/1703.09474)

##### PDF
[https://arxiv.org/pdf/1703.09474](https://arxiv.org/pdf/1703.09474)

