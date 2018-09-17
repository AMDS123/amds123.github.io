---
layout: post
title: "Unsupervised Learning for Fast Probabilistic Diffeomorphic Registration"
date: 2018-09-14 13:28:36
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Inference
author: Adrian V. Dalca, Guha Balakrishnan, John Guttag, Mert R. Sabuncu
mathjax: true
---

* content
{:toc}

##### Abstract
Traditional deformable registration techniques achieve impressive results and offer a rigorous theoretical treatment, but are computationally intensive since they solve an optimization problem for each image pair. Recently, learning-based methods have facilitated fast registration by learning spatial deformation functions. However, these approaches use restricted deformation models, require supervised labels, or do not guarantee a diffeomorphic (topology-preserving) registration. Furthermore, learning-based registration tools have not been derived from a probabilistic framework that can offer uncertainty estimates. In this paper, we present a probabilistic generative model and derive an unsupervised learning-based inference algorithm that makes use of recent developments in convolutional neural networks (CNNs). We demonstrate our method on a 3D brain registration task, and provide an empirical analysis of the algorithm. Our approach results in state of the art accuracy and very fast runtimes, while providing diffeomorphic guarantees and uncertainty estimates. Our implementation is available online at <a href="http://voxelmorph.csail.mit.edu">this http URL</a> .

##### Abstract (translated by Google)
传统的可变形配准技术取得了令人瞩目的成果，并提供了严格的理论处理，但计算量很大，因为它们解决了每个图像对的优化问题。最近，基于学习的方法通过学习空间变形函数促进了快速配准。然而，这些方法使用受限制的变形模型，需要监督标签，或者不保证差异形态（拓扑保持）注册。此外，基于学习的注册工具尚未从可提供不确定性估计的概率框架中得出。在本文中，我们提出了一个概率生成模型，并推导出一种无监督的基于学习的推理算法，该算法利用了卷积神经网络（CNNs）的最新发展。我们在3D脑注册任务上演示了我们的方法，并提供了算法的实证分析。我们的方法产生了最先进的精度和非常快的运行时间，同时提供了不同的保证和不确定性估计。我们的实施可在<a href="http://voxelmorph.csail.mit.edu">此http URL </a>在线获取。

##### URL
[http://arxiv.org/abs/1805.04605](http://arxiv.org/abs/1805.04605)

##### PDF
[http://arxiv.org/pdf/1805.04605](http://arxiv.org/pdf/1805.04605)

