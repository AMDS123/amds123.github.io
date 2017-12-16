---
layout: post
title: "A Harmonic Mean Linear Discriminant Analysis for Robust Image Classification"
date: 2016-10-24 16:38:29
categories: arXiv_CV
tags: arXiv_CV Image_Classification Classification Recognition
author: Shuai Zheng, Feiping Nie, Chris Ding, Heng Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Linear Discriminant Analysis (LDA) is a widely-used supervised dimensionality reduction method in computer vision and pattern recognition. In null space based LDA (NLDA), a well-known LDA extension, between-class distance is maximized in the null space of the within-class scatter matrix. However, there are some limitations in NLDA. Firstly, for many data sets, null space of within-class scatter matrix does not exist, thus NLDA is not applicable to those datasets. Secondly, NLDA uses arithmetic mean of between-class distances and gives equal consideration to all between-class distances, which makes larger between-class distances can dominate the result and thus limits the performance of NLDA. In this paper, we propose a harmonic mean based Linear Discriminant Analysis, Multi-Class Discriminant Analysis (MCDA), for image classification, which minimizes the reciprocal of weighted harmonic mean of pairwise between-class distance. More importantly, MCDA gives higher priority to maximize small between-class distances. MCDA can be extended to multi-label dimension reduction. Results on 7 single-label data sets and 4 multi-label data sets show that MCDA has consistently better performance than 10 other single-label approaches and 4 other multi-label approaches in terms of classification accuracy, macro and micro average F1 score.

##### Abstract (translated by Google)
线性判别分析（LDA）是一种在计算机视觉和模式识别中广泛使用的有监督降维方法。在基于零空间的LDA（NLDA）中，一个众所周知的LDA扩展中，类间距离在类内散布矩阵的零空间中被最大化。但是，NLDA有一些限制。首先，对于许多数据集，不存在类内散布矩阵的零空间，因此NLDA不适用于这些数据集。其次，NLDA使用类间距离的算术平均值，同时考虑所有的类间距离，这使得更大的类间距离可以支配结果，从而限制了NLDA的性能。在本文中，我们提出了一种基于调和平均的线性判别分析，多级判别分析（MCDA），用于图像分类，使得两两之间的加权调和平均数的倒数最小。更重要的是，MCDA给予更高的优先级来最大化小班间距离。 MCDA可以扩展到多标签降维。 7个单标签数据集和4个多标签数据集的结果表明，MCDA在分类准确性，宏观和微观平均F1得分方面，比其他10种单标签方法和4种其他多标签方法具有更好的性能。

##### URL
[https://arxiv.org/abs/1610.04631](https://arxiv.org/abs/1610.04631)

##### PDF
[https://arxiv.org/pdf/1610.04631](https://arxiv.org/pdf/1610.04631)

