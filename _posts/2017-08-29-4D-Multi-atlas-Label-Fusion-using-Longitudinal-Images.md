---
layout: post
title: "4D Multi-atlas Label Fusion using Longitudinal Images"
date: 2017-08-29 15:33:53
categories: arXiv_CV
tags: arXiv_CV Segmentation Face
author: Yuankai Huo, Susan M. Resnick, Bennett A. Landman
mathjax: true
---

* content
{:toc}

##### Abstract
Longitudinal reproducibility is an essential concern in automated medical image segmentation, yet has proven to be an elusive objective as manual brain structure tracings have shown more than 10% variability. To improve reproducibility, lon-gitudinal segmentation (4D) approaches have been investigated to reconcile tem-poral variations with traditional 3D approaches. In the past decade, multi-atlas la-bel fusion has become a state-of-the-art segmentation technique for 3D image and many efforts have been made to adapt it to a 4D longitudinal fashion. However, the previous methods were either limited by using application specified energy function (e.g., surface fusion and multi model fusion) or only considered tem-poral smoothness on two consecutive time points (t and t+1) under sparsity as-sumption. Therefore, a 4D multi-atlas label fusion theory for general label fusion purpose and simultaneously considering temporal consistency on all time points is appealing. Herein, we propose a novel longitudinal label fusion algorithm, called 4D joint label fusion (4DJLF), to incorporate the temporal consistency modeling via non-local patch-intensity covariance models. The advantages of 4DJLF include: (1) 4DJLF is under the general label fusion framework by simul-taneously incorporating the spatial and temporal covariance on all longitudinal time points. (2) The proposed algorithm is a longitudinal generalization of a lead-ing joint label fusion method (JLF) that has proven adaptable to a wide variety of applications. (3) The spatial temporal consistency of atlases is modeled in a prob-abilistic model inspired from both voting based and statistical fusion. The pro-posed approach improves the consistency of the longitudinal segmentation while retaining sensitivity compared with original JLF approach using the same set of atlases. The method is available online in open-source.

##### Abstract (translated by Google)
纵向再现性是自动医学图像分割中的一个重要问题，但已经被证明是一个难以捉摸的目标，因为人工大脑结构描记显示超过10％的变异性。为了提高可重复性，已经研究了纵向分割（4D）方法来协调时间变化与传统的3D方法。在过去的十年里，多图集la-bel融合已经成为3D图像的最先进的分割技术，并且已经做出许多努力来使其适应于四维纵向方式。然而，在稀疏度假设下，两个连续的时间点（t和t + 1），以前的方法要么通过使用应用指定的能量函数（例如表面融合和多模型融合）或仅考虑时间平滑性来限制。因此，对于一般标签融合目的而言，同时考虑所有时间点上的时间一致性的四维多图集标签融合理论是有吸引力的。在这里，我们提出了一种新的纵向标签融合算法，称为4D联合标签融合（4DJLF），通过非局部区块 - 强度协方差模型整合时间一致性建模。 4DJLF的优点包括：（1）4DJLF属于通用标签融合框架，同时在所有纵向时间点上包含空间和时间协方差。 （2）提出的算法是一种领先的联合标签融合方法（JLF）的纵向推广，已被证明适用于各种各样的应用。 （3）地图集的空间时间一致性模型是基于投票和统计融合的概率模型。与原始JLF方法相比，该方法提高了纵向分割的一致性，同时保留了灵敏度。该方法可在线获取开放源代码。

##### URL
[https://arxiv.org/abs/1708.08825](https://arxiv.org/abs/1708.08825)

##### PDF
[https://arxiv.org/pdf/1708.08825](https://arxiv.org/pdf/1708.08825)

