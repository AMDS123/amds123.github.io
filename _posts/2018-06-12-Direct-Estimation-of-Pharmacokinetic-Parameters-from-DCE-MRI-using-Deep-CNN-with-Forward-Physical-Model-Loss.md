---
layout: post
title: "Direct Estimation of Pharmacokinetic Parameters from DCE-MRI using Deep CNN with Forward Physical Model Loss"
date: 2018-06-12 11:34:14
categories: arXiv_CV
tags: arXiv_CV Knowledge Inference Deep_Learning Quantitative
author: Cagdas Ulas, Giles Tetteh, Michael J. Thrippleton, Paul A. Armitage, Stephen D. Makin, Joanna M. Wardlaw, Mike E. Davies, Bjoern H. Menze
mathjax: true
---

* content
{:toc}

##### Abstract
Dynamic contrast-enhanced (DCE) MRI is an evolving imaging technique that provides a quantitative measure of pharmacokinetic (PK) parameters in body tissues, in which series of T1-weighted images are collected following the administration of a paramagnetic contrast agent. Unfortunately, in many applications, conventional clinical DCE-MRI suffers from low spatiotemporal resolution and insufficient volume coverage. In this paper, we propose a novel deep learning based approach to directly estimate the PK parameters from undersampled DCE-MRI data. Specifically, we design a custom loss function where we incorporate a forward physical model that relates the PK parameters to corrupted image-time series obtained due to subsampling in k-space. This allows the network to directly exploit the knowledge of true contrast agent kinetics in the training phase, and hence provide more accurate restoration of PK parameters. Experiments on clinical brain DCE datasets demonstrate the efficacy of our approach in terms of fidelity of PK parameter reconstruction and significantly faster parameter inference compared to a model-based iterative reconstruction method.

##### Abstract (translated by Google)
动态对比增强（DCE）MRI是一种不断发展的成像技术，可提供对人体组织中药物动力学（PK）参数的定量测量，其中采用顺磁造影剂后收集一系列T1加权像。不幸的是，在许多应用中，传统的临床DCE-MRI遭受低时空分辨率和不足容量覆盖。在本文中，我们提出了一种新颖的基于深度学习的方法来直接估算欠采样DCE-MRI数据的PK参数。具体而言，我们设计了一个自定义损失函数，我们将一个正向物理模型与PK参数相关联，以便将k参数与由于k空间中的子采样而获得的损坏的图像时间序列相关联。这使得网络可以直接利用训练阶段真实造影剂动力学的知识，从而提供更准确的PK参数恢复。临床大脑DCE数据集的实验证明了我们的方法在PK参数重构的保真度方面的效力以及与基于模型的迭代重建方法相比显着更快的参数推断。

##### URL
[http://arxiv.org/abs/1804.02745](http://arxiv.org/abs/1804.02745)

##### PDF
[http://arxiv.org/pdf/1804.02745](http://arxiv.org/pdf/1804.02745)

