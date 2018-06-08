---
layout: post
title: "Nonparametric Density Flows for MRI Intensity Normalisation"
date: 2018-06-07 11:13:35
categories: arXiv_CV
tags: arXiv_CV
author: Daniel C. Castro, Ben Glocker
mathjax: true
---

* content
{:toc}

##### Abstract
With the adoption of powerful machine learning methods in medical image analysis, it is becoming increasingly desirable to aggregate data that is acquired across multiple sites. However, the underlying assumption of many analysis techniques that corresponding tissues have consistent intensities in all images is often violated in multi-centre databases. We introduce a novel intensity normalisation scheme based on density matching, wherein the histograms are modelled as Dirichlet process Gaussian mixtures. The source mixture model is transformed to minimise its $L^2$ divergence towards a target model, then the voxel intensities are transported through a mass-conserving flow to maintain agreement with the moving density. In a multi-centre study with brain MRI data, we show that the proposed technique produces excellent correspondence between the matched densities and histograms. We further demonstrate that our method makes tissue intensity statistics substantially more compatible between images than a baseline affine transformation and is comparable to state-of-the-art while providing considerably smoother transformations. Finally, we validate that nonlinear intensity normalisation is a step toward effective imaging data harmonisation.

##### Abstract (translated by Google)
随着在医学图像分析中采用功能强大的机器学习方法，越来越需要汇总跨多个站点采集的数据。然而，在多中心数据库中常常违反了相应组织在所有图像中具有一致强度的许多分析技术的潜在假设。我们引入了一种基于密度匹配的新型强度归一化方案，其中直方图被建模为Dirichlet过程高斯混合。对源混合模型进行变换以使其对目标模型的散射最小化，然后将体素强度通过质量保持流传输以保持与移动密度一致。在一项有关脑部MRI数据的多中心研究中，我们表明所提出的技术在匹配的密度和直方图之间产生了很好的对应关系。我们进一步证明，我们的方法使得组织强度统计数据在图像之间比基线仿射变换更加兼容，并且与最先进的技术相媲美，同时提供相当平滑的变换。最后，我们验证非线性强度归一化是实现有效成像数据协调的一个步骤。

##### URL
[http://arxiv.org/abs/1806.02613](http://arxiv.org/abs/1806.02613)

##### PDF
[http://arxiv.org/pdf/1806.02613](http://arxiv.org/pdf/1806.02613)

