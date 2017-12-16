---
layout: post
title: "Multi-View Surveillance Video Summarization via Joint Embedding and Sparse Optimization"
date: 2017-06-09 20:56:20
categories: arXiv_CV
tags: arXiv_CV Sparse Summarization Embedding Optimization Relation
author: Rameswar Panda, Amit K. Roy-Chowdhury
mathjax: true
---

* content
{:toc}

##### Abstract
Most traditional video summarization methods are designed to generate effective summaries for single-view videos, and thus they cannot fully exploit the complicated intra and inter-view correlations in summarizing multi-view videos in a camera network. In this paper, with the aim of summarizing multi-view videos, we introduce a novel unsupervised framework via joint embedding and sparse representative selection. The objective function is two-fold. The first is to capture the multi-view correlations via an embedding, which helps in extracting a diverse set of representatives. The second is to use a `2;1- norm to model the sparsity while selecting representative shots for the summary. We propose to jointly optimize both of the objectives, such that embedding can not only characterize the correlations, but also indicate the requirements of sparse representative selection. We present an efficient alternating algorithm based on half-quadratic minimization to solve the proposed non-smooth and non-convex objective with convergence analysis. A key advantage of the proposed approach with respect to the state-of-the-art is that it can summarize multi-view videos without assuming any prior correspondences/alignment between them, e.g., uncalibrated camera networks. Rigorous experiments on several multi-view datasets demonstrate that our approach clearly outperforms the state-of-the-art methods.

##### Abstract (translated by Google)
大多数传统的视频摘要方法被设计为生成单视点视频的有效摘要，因此不能充分利用复杂的帧内和视点间相关性来总结相机网络中的多视点视频。为了总结多视点视频，本文通过联合嵌入和稀疏代表性选择，引入了一种新的无监督框架。目标函数是双重的。首先是通过嵌入捕获多视图相关性，这有助于提取多种代表。其次是使用一个“2”1-范数来为稀疏性建模，同时为摘要选择代表性镜头。我们提出对这两个目标进行联合优化，使得嵌入不仅可以表征相关性，还可以表示稀疏代表性选择的要求。本文提出了一种基于半二次最小化的有效交替算法，通过收敛性分析来解决非光滑非凸目标问题。所提出的关于现有技术的方法的主要优点在于，它可以总结多视点视频而不假定它们之间的任何先前的对应/对准，例如未校准的相机网络。对多个多视图数据集的严格实验表明，我们的方法明显优于最先进的方法。

##### URL
[https://arxiv.org/abs/1706.03121](https://arxiv.org/abs/1706.03121)

##### PDF
[https://arxiv.org/pdf/1706.03121](https://arxiv.org/pdf/1706.03121)

