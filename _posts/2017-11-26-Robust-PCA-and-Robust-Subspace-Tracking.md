---
layout: post
title: "Robust PCA and Robust Subspace Tracking"
date: 2017-11-26 23:52:53
categories: arXiv_CV
tags: arXiv_CV Tracking
author: Namrata Vaswani, Thierry Bouwmans, Sajid Javed, Praneeth Narayanamurthy
mathjax: true
---

* content
{:toc}

##### Abstract
Principal Components Analysis (PCA) is one of the most widely used dimension reduction techniques. Given a matrix of clean data, PCA is easily accomplished via singular value decomposition (SVD) on the data matrix. While PCA for relatively clean data is an easy and solved problem, it becomes much harder if the data is corrupted by even a few outliers. The reason is that SVD is sensitive to outliers. In today's big data age, since data is often acquired using a large number of inexpensive sensors, outliers are becoming even more common. This harder problem of PCA for outlier corrupted data is called robust PCA. Often, for long data sequences, e.g., long surveillance videos, if one tries to use a single lower dimensional subspace to represent the data, the required subspace dimension may end up being quite large. For such data, a better model is to assume that it lies in a low-dimensional subspace that can change over time, albeit gradually. The problem of tracking a (slowly) changing subspace over time is often referred to as "subspace tracking" or "dynamic PCA". The problem of tracking it in the presence of outliers can thus be called either "robust subspace tracking" or "dynamic robust PCA". This article provides a comprehensive tutorial-style overview of the robust and dynamic robust PCA problems and solution approaches, with an emphasis on simple and provably correct approaches.

##### Abstract (translated by Google)
主成分分析（PCA）是应用最广泛的降维技术之一。给定一个干净的数据矩阵，PCA很容易通过数据矩阵上的奇异值分解（SVD）来完成。虽然相对干净的数据的PCA是一个简单和解决的问题，但是如果数据被几个异常值破坏就变得困难得多。原因是奇异值分解对于异常点很敏感。在当今的大数据时代，由于数据通常是使用大量廉价的传感器获取的，因此异常值变得更加普遍。对于异常数据损坏的PCA这个难度较大的问题称为稳健PCA。通常，对于长数据序列（例如，长监视视频），如果试图使用单个较低维度的子空间来表示数据，则所需的子空间维度可能最终非常大。对于这样的数据来说，更好的模型是假设它位于可以随时间变化的低维子空间中，尽管是逐渐变化的。随着时间追踪（缓慢）变化子空间的问题通常被称为“子空间追踪”或“动态PCA”。因此，在存在异常值的情况下跟踪它的问题可以称为“鲁棒子空间跟踪”或“动态鲁棒PCA”。本文提供了强大的动态健壮的PCA问题和解决方案的综合教程式概述，强调简单和可证明的正确方法。

##### URL
[https://arxiv.org/abs/1711.09492](https://arxiv.org/abs/1711.09492)

##### PDF
[https://arxiv.org/pdf/1711.09492](https://arxiv.org/pdf/1711.09492)

