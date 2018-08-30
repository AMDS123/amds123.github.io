---
layout: post
title: "Cross-Domain Collaborative Learning via Cluster Canonical Correlation Analysis and Random Walker for Hyperspectral Image Classification"
date: 2018-08-29 11:37:23
categories: arXiv_CV
tags: arXiv_CV Segmentation Image_Classification Classification Relation
author: Yao Qin, Biao Li, Yuanxin Ye
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces a novel heterogenous domain adaptation (HDA) method for hyperspectral image classification with a limited amount of labeled samples in both domains. The method is achieved in the way of cross-domain collaborative learning (CDCL), which is addressed via cluster canonical correlation analysis (C-CCA) and random walker (RW) algorithms. To be specific, the proposed CDCL method is an iterative process of three main stages, i.e. twice of RW-based pseudolabeling and cross domain learning via C-CCA. Firstly, given the initially labeled target samples as training set ($\mathbf{TS}$), the RW-based pseudolabeling is employed to update $\mathbf{TS}$ and extract target clusters ($\mathbf{TCs}$) by fusing the segmentation results obtained by RW and extended RW (ERW) classifiers. Secondly, cross domain learning via C-CCA is applied using labeled source samples and $\mathbf{TCs}$. The unlabeled target samples are then classified with the estimated probability maps using the model trained in the projected correlation subspace. Thirdly, both $\mathbf{TS}$ and estimated probability maps are used for updating $\mathbf{TS}$ again via RW-based pseudolabeling. When the iterative process finishes, the result obtained by the ERW classifier using the final $\mathbf{TS}$ and estimated probability maps is regarded as the final classification map. Experimental results on four real HSIs demonstrate that the proposed method can achieve better performance compared with the state-of-the-art HDA and ERW methods.

##### Abstract (translated by Google)
本文介绍了一种新的异质域适应（HDA）方法，用于高光谱图像分类，两个域中的标记样本数量有限。该方法以跨域协作学习（CDCL）的方式实现，其通过集群规范相关分析（C-CCA）和随机游走（RW）算法来解决。具体而言，所提出的CDCL方法是三个主要阶段的迭代过程，即基于RW的伪标记和通过C-CCA的跨域学习的两倍。首先，给出最初标记的目标样本作为训练集（$ \ mathbf {TS} $），基于RW的伪标记用于更新$ \ mathbf {TS} $并提取目标集群（$ \ mathbf {TCs} $）通过融合RW和扩展RW（ERW）分类器获得的分割结果。其次，使用标记的源样本和$ \ mathbf {TCs} $应用通过C-CCA的跨域学习。然后使用在投影相关子空间中训练的模型，用估计的概率图对未标记的目标样本进行分类。第三，$ \ mathbf {TS} $和估计概率图都用于通过基于RW的伪标记再次更新$ \ mathbf {TS} $。当迭代过程结束时，ERW分类器使用最终$ \ mathbf {TS} $和估计概率图获得的结果被视为最终分类图。四个真实HSI的实验结果表明，与现有技术的HDA和ERW方法相比，所提出的方法可以获得更好的性能。

##### URL
[http://arxiv.org/abs/1808.09740](http://arxiv.org/abs/1808.09740)

##### PDF
[http://arxiv.org/pdf/1808.09740](http://arxiv.org/pdf/1808.09740)

