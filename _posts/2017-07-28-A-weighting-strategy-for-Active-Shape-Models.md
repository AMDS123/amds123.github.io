---
layout: post
title: "A weighting strategy for Active Shape Models"
date: 2017-07-28 13:55:56
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Detection
author: Alma Eguizabal, Peter J. Schreier
mathjax: true
---

* content
{:toc}

##### Abstract
Active Shape Models (ASM) are an iterative segmentation technique to find a landmark-based contour of an object. In each iteration, a least-squares fit of a plausible shape to some detected target landmarks is determined. Finding these targets is a critical step: some landmarks are more reliably detected than others, and some landmarks may not be within the field of view of their detectors. To add robustness while preserving simplicity at the same time, a generalized least-squares approach can be used, where a weighting matrix incorporates reliability information about the landmarks. We propose a strategy to choose this matrix, based on the covariance of empirically determined residuals of the fit. We perform a further step to determine whether the target landmarks are within the range of their detectors. We evaluate our strategy on fluoroscopic X-ray images to segment the femur. We show that our technique outperforms the standard ASM as well as other more heuristic weighted least-squares strategies.

##### Abstract (translated by Google)
主动形状模型（ASM）是一种迭代分割技术，用于查找基于地标的物体轮廓。在每次迭代中，确定对于一些检测到的目标地标的似真形状的最小二乘拟合。找到这些目标是一个关键步骤：一些地标比其他地标更可靠地被发现，一些地标可能不在其探测器的视野内。为了在保持简单性的同时增加鲁棒性，可以使用广义最小二乘法，其中加权矩阵包含关于地标的可靠性信息。我们提出了一个基于经验确定的拟合残差的协方差来选择这个矩阵的策略。我们进一步确定目标地标是否在探测器范围内。我们评估我们的X线透视图像分割股骨的策略。我们表明，我们的技术胜过标准的ASM以及其他更多的启发式加权最小二乘策略。

##### URL
[https://arxiv.org/abs/1707.09233](https://arxiv.org/abs/1707.09233)

##### PDF
[https://arxiv.org/pdf/1707.09233](https://arxiv.org/pdf/1707.09233)

