---
layout: post
title: "Robust Kronecker-Decomposable Component Analysis for Low-Rank Modeling"
date: 2017-07-26 14:50:13
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Mehdi Bahri, Yannis Panagakis, Stefanos Zafeiriou
mathjax: true
---

* content
{:toc}

##### Abstract
Dictionary learning and component analysis are part of one of the most well-studied and active research fields, at the intersection of signal and image processing, computer vision, and statistical machine learning. In dictionary learning, the current methods of choice are arguably K-SVD and its variants, which learn a dictionary (i.e., a decomposition) for sparse coding via Singular Value Decomposition. In robust component analysis, leading methods derive from Principal Component Pursuit (PCP), which recovers a low-rank matrix from sparse corruptions of unknown magnitude and support. However, K-SVD is sensitive to the presence of noise and outliers in the training set. Additionally, PCP does not provide a dictionary that respects the structure of the data (e.g., images), and requires expensive SVD computations when solved by convex relaxation. In this paper, we introduce a new robust decomposition of images by combining ideas from sparse dictionary learning and PCP. We propose a novel Kronecker-decomposable component analysis which is robust to gross corruption, can be used for low-rank modeling, and leverages separability to solve significantly smaller problems. We design an efficient learning algorithm by drawing links with a restricted form of tensor factorization. The effectiveness of the proposed approach is demonstrated on real-world applications, namely background subtraction and image denoising, by performing a thorough comparison with the current state of the art.

##### Abstract (translated by Google)
字典学习和分量分析是信号与图像处理，计算机视觉和统计机器学习交叉研究领域中研究最为活跃的研究领域之一。在字典学习中，当前的选择方法可以说是K-SVD及其变体，它们通过奇异值分解学习用于稀疏编码的字典（即，分解）。在鲁棒分量分析中，主要方法来自主成分追踪（PCP），它从未知量和支持的稀疏腐败中恢复出一个低秩矩阵。然而，K-SVD对于训练集中存在噪声和异常值是敏感的。此外，PCP不提供尊重数据结构（例如图像）的字典，并且当通过凸松弛求解时需要昂贵的SVD计算。在本文中，我们通过结合稀疏字典学习和PCP的思想来引入图像的新的鲁棒分解。我们提出了一种新的克罗内克分解分量分析，它对粗糙的腐败是鲁棒的，可以用于低秩建模，并利用可分性来解决显着较小的问题。我们设计一个有效的学习算法，通过绘制与张量分解的限制形式的链接。所提出的方法的有效性通过与现有技术进行彻底的比较而在现实世界的应用（即背景减除和图像去噪）上得到证明。

##### URL
[https://arxiv.org/abs/1703.07886](https://arxiv.org/abs/1703.07886)

##### PDF
[https://arxiv.org/pdf/1703.07886](https://arxiv.org/pdf/1703.07886)

