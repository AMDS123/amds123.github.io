---
layout: post
title: "Total Variation Regularized Tensor RPCA for Background Subtraction from Compressive Measurements"
date: 2016-06-05 17:46:14
categories: arXiv_CV
tags: arXiv_CV Relation
author: Wenfei Cao, Yao Wang, Jian Sun, Deyu Meng, Can Yang, Andrzej Cichocki, Zongben Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Background subtraction has been a fundamental and widely studied task in video analysis, with a wide range of applications in video surveillance, teleconferencing and 3D modeling. Recently, motivated by compressive imaging, background subtraction from compressive measurements (BSCM) is becoming an active research task in video surveillance. In this paper, we propose a novel tensor-based robust PCA (TenRPCA) approach for BSCM by decomposing video frames into backgrounds with spatial-temporal correlations and foregrounds with spatio-temporal continuity in a tensor framework. In this approach, we use 3D total variation (TV) to enhance the spatio-temporal continuity of foregrounds, and Tucker decomposition to model the spatio-temporal correlations of video background. Based on this idea, we design a basic tensor RPCA model over the video frames, dubbed as the holistic TenRPCA model (H-TenRPCA). To characterize the correlations among the groups of similar 3D patches of video background, we further design a patch-group-based tensor RPCA model (PG-TenRPCA) by joint tensor Tucker decompositions of 3D patch groups for modeling the video background. Efficient algorithms using alternating direction method of multipliers (ADMM) are developed to solve the proposed models. Extensive experiments on simulated and real-world videos demonstrate the superiority of the proposed approaches over the existing state-of-the-art approaches.

##### Abstract (translated by Google)
背景减法一直是视频分析中的一项基础性和广泛研究的任务，在视频监控，电话会议和三维建模方面具有广泛的应用。近年来，随着压缩成像技术的发展，压缩测量背景扣除（BSCM）成为视频监控领域的一项研究热点。在本文中，我们提出了一种新颖的基于张量的稳健PCA（TenRPCA）方法，通过将视频帧分解为具有时空相关性的背景和在张量框架中具有时空连续性的前景。在这种方法中，我们使用三维全变差（TV）来增强前景的时空连续性，而Tucker分解来模拟视频背景的时空相关性。基于这个思想，我们在视频帧上设计了基本张量RPCA模型，称为整体TenRPCA模型（H-TenRPCA）。为了表征视频背景的相似3D片段之间的相关性，我们进一步通过三维片组的联合张量Tucker分解来设计基于片组的张量RPCA模型（PG-TenRPCA），以对视频背景进行建模。利用交替方向乘法器（ADMM）的有效算法来求解所提出的模型。对模拟和真实世界的视频进行大量的实验证明了所提出的方法优于现有的最先进的方法。

##### URL
[https://arxiv.org/abs/1503.01868](https://arxiv.org/abs/1503.01868)

##### PDF
[https://arxiv.org/pdf/1503.01868](https://arxiv.org/pdf/1503.01868)

