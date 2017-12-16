---
layout: post
title: "Dominant Sets for 'Constrained' Image Segmentation"
date: 2017-07-15 03:32:42
categories: arXiv_CV
tags: arXiv_CV Regularization Segmentation Optimization
author: Eyasu Zemene, Leulseged Tesfaye Alemu, Marcello Pelillo
mathjax: true
---

* content
{:toc}

##### Abstract
Image segmentation has come a long way since the early days of computer vision, and still remains a challenging task. Modern variations of the classical (purely bottom-up) approach, involve, e.g., some form of user assistance (interactive segmentation) or ask for the simultaneous segmentation of two or more images (co-segmentation). At an abstract level, all these variants can be thought of as "constrained" versions of the original formulation, whereby the segmentation process is guided by some external source of information. In this paper, we propose a new approach to tackle this kind of problems in a unified way. Our work is based on some properties of a family of quadratic optimization problems related to dominant sets, a well-known graph-theoretic notion of a cluster which generalizes the concept of a maximal clique to edge-weighted graphs. In particular, we show that by properly controlling a regularization parameter which determines the structure and the scale of the underlying problem, we are in a position to extract groups of dominant-set clusters that are constrained to contain predefined elements. In particular, we shall focus on interactive segmentation and co-segmentation (in both the unsupervised and the interactive versions). The proposed algorithm can deal naturally with several type of constraints and input modality, including scribbles, sloppy contours, and bounding boxes, and is able to robustly handle noisy annotations on the part of the user. Experiments on standard benchmark datasets show the effectiveness of our approach as compared to state-of-the-art algorithms on a variety of natural images under several input conditions and constraints.

##### Abstract (translated by Google)
从计算机视觉的早期开始，图像分割就有了很长的路要走，而且仍然是一个具有挑战性的任务。经典（纯粹自下而上）方法的现代变体涉及例如某种形式的用户帮助（交互式分割）或要求两个或更多个图像的同时分割（共分割）。在抽象层面上，所有这些变体都可以被认为是原始公式的“受限”版本，因此分割过程由一些外部信息来源引导。在本文中，我们提出了一种统一处理这类问题的新方法。我们的工作是基于与显性集相关的一族二次优化问题的一些性质，这是一个众所周知的图的群理论概念，它将最大团概念推广到边加权图。具体来说，我们通过适当地控制一个正则化参数来确定潜在问题的结构和规模，我们可以提取被约束为包含预定义元素的显性集合群组。特别是，我们将重点关注交互式分割和协同分割（在无监督和交互式版本中）。提出的算法可以自然处理几种约束条件和输入形式，包括涂鸦，粗糙的轮廓和边界框，能够强有力地处理用户部分的嘈杂注释。标准基准数据集上的实验表明，我们的方法与多种输入条件和约束条件下的各种自然图像中的最新算法相比较的有效性。

##### URL
[https://arxiv.org/abs/1707.05309](https://arxiv.org/abs/1707.05309)

##### PDF
[https://arxiv.org/pdf/1707.05309](https://arxiv.org/pdf/1707.05309)

