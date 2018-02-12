---
layout: post
title: "Piecewise Flat Embedding for Image Segmentation"
date: 2018-02-09 13:19:14
categories: arXiv_CV
tags: arXiv_CV Image_Caption Regularization Sparse Segmentation Embedding Detection
author: Chaowei Fang, Zicheng Liao, Yizhou Yu
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new nonlinear embedding -- Piecewise Flat Embedding (PFE) -- for image segmentation. Based on the theory of sparse signal recovery, piecewise flat embedding attempts to recover a piecewise constant image representation with sparse region boundaries and sparse cluster value scattering. The resultant piecewise flat embedding exhibits interesting properties such as suppressing slowly varying signals, and offers an image representation with higher region identifiability which is desirable for image segmentation or high-level semantic analysis tasks. We formulate our embedding as a variant of the Laplacian Eigenmap embedding with an $L_{1,p} (0&lt;p\leq1)$ regularization term to promote sparse solutions. First, we devise a two-stage numerical algorithm based on Bregman iterations to compute $L_{1,1}$-regularized piecewise flat embeddings. We further generalize this algorithm through iterative reweighting to solve the general $L_{1,p}$-regularized problem. To demonstrate its efficacy, we integrate PFE into two existing image segmentation frameworks, segmentation based on clustering and hierarchical segmentation based on contour detection. Experiments on three major benchmark datasets, BSDS500, MSRC, Stanford Background Dataset, and PASCAL Context, show that segmentation algorithms incorporating our embedding achieve significantly improved results.

##### Abstract (translated by Google)
我们提出了一种新的非线性嵌入 - 分段平坦嵌入（PFE） - 图像分割。基于稀疏信号恢复理论，分段平坦嵌入试图恢复具有稀疏区域边界和稀疏簇值散射的分段恒定图像表示。合成的分段平坦嵌入表现出令人感兴趣的特性，例如抑制缓慢变化的信号，并且提供具有较高区域可识别性的图像表示，这对于图像分割或高级语义分析任务是理想的。我们使用$ L_ {1，p}（0 <p \ leq1）$正则化项来嵌入Laplacian Eigenmap嵌入的变体，以推广稀疏解。首先，我们设计一个基于Bregman迭代的两阶段数值算法来计算$ L_ {1,1} $  - 正则化分段平坦嵌入。我们通过迭代重新加权来进一步推广这个算法来解决一般的$ L_ {1，p} $正则化问题。为了展示其功效，我们将PFE整合到两个现有的图像分割框架中，基于聚类和基于轮廓检测的分层分割进行分割。对三个主要基准数据集BSDS500，MSRC，Stanford Background Dataset和PASCAL Context进行的实验表明，结合我们的嵌入的分割算法实现了显着改善的结果。

##### URL
[http://arxiv.org/abs/1802.03248](http://arxiv.org/abs/1802.03248)

##### PDF
[http://arxiv.org/pdf/1802.03248](http://arxiv.org/pdf/1802.03248)

