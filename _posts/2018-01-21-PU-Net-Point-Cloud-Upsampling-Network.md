---
layout: post
title: "PU-Net: Point Cloud Upsampling Network"
date: 2018-01-21 04:10:52
categories: arXiv_CV
tags: arXiv_CV Sparse Face Optimization
author: Lequan Yu, Xianzhi Li, Chi-Wing Fu, Daniel Cohen-Or, Pheng-Ann Heng
mathjax: true
---

* content
{:toc}

##### Abstract
Learning and analyzing 3D point cloud with deep networks is challenging due to the sparseness and irregularity of the data. In this paper, we present a data-driven point cloud upsampling technique. The key idea is to learn multi-level features per point, and then expanding them via a multi-branch convolution unit, to implicitly expand the point set in feature space. The expanded feature is then split to a multitude of features, which are then reconstructed to an upsampled point set. Our network is applied at a patch-level, with a joint loss function that encourages the upsampled points to remain on the underlying surface with a uniform distribution. We conduct various experiments using synthesis and scan data to evaluate our method and demonstrate its superiority over some baseline methods and an optimization-based method. The results show that our upsampled results have better uniformity, and sampled closer to the underlying surface.

##### Abstract (translated by Google)
由于数据的稀疏性和不规则性，使用深度网络来学习和分析3D点云是具有挑战性的。在本文中，我们提出了一个数据驱动的点云上采样技术。关键是要学习每个点的多级特征，然后通过多分支卷积单元进行扩展，以隐式扩展特征空间中的点集。然后将展开的特征分割成多个特征，然后重建为上采样点集。我们的网络以补丁级应用，具有联合损失功能，鼓励上采样点以均匀的分布保留在下面的表面上。我们使用综合和扫描数据进行各种实验来评估我们的方法，并证明其优于一些基线方法和基于优化的方法。结果表明，我们的上采样结果具有更好的一致性，并采样更接近底层表面。

##### URL
[https://arxiv.org/abs/1801.06761](https://arxiv.org/abs/1801.06761)

##### PDF
[https://arxiv.org/pdf/1801.06761](https://arxiv.org/pdf/1801.06761)

