---
layout: post
title: "FastFCA: A Joint Diagonalization Based Fast Algorithm for Audio Source Separation Using A Full-Rank Spatial Covariance Model"
date: 2018-05-17 01:47:14
categories: arXiv_SD
tags: arXiv_SD
author: Nobutaka Ito, Shoko Araki, Tomohiro Nakatani
mathjax: true
---

* content
{:toc}

##### Abstract
A source separation method using a full-rank spatial covariance model has been proposed by Duong et al. ["Under-determined Reverberant Audio Source Separation Using a Full-rank Spatial Covariance Model," IEEE Trans. ASLP, vol. 18, no. 7, pp. 1830-1840, Sep. 2010], which is referred to as full-rank spatial covariance analysis (FCA) in this paper. Here we propose a fast algorithm for estimating the model parameters of the FCA, which is named Fast-FCA, and applicable to the two-source case. Though quite effective in source separation, the conventional FCA has a major drawback of expensive computation. Indeed, the conventional algorithm for estimating the model parameters of the FCA requires frame-wise matrix inversion and matrix multiplication. Therefore, the conventional FCA may be infeasible in applications with restricted computational resources. In contrast, the proposed FastFCA bypasses matrix inversion and matrix multiplication owing to joint diagonalization based on the generalized eigenvalue problem. Furthermore, the FastFCA is strictly equivalent to the conventional algorithm. An experiment has shown that the FastFCA was over 250 times faster than the conventional algorithm with virtually the same source separation performance.

##### Abstract (translated by Google)
Duong等人已经提出了使用全秩空间协方差模型的源分离方法。 [“使用全秩空间协方差模型的欠定混响音频源分离”，IEEE Trans。 ASLP，vol。 18，没有。 7，pp。1830-1840，2010年9月]，在本文中被称为全秩空间协方差分析（FCA）。在这里我们提出了一种快速估算FCA模型参数的算法，它被命名为Fast-FCA，并且适用于双源的情况。尽管在源分离方面非常有效，但是传统的FCA具有昂贵计算的主要缺点。确实，用于估计FCA的模型参数的常规算法需要逐帧矩阵求逆和矩阵乘法。因此，传统的FCA在计算资源有限的应用中可能是不可行的。相反，由于基于广义特征值问题的联合对角化，所提出的FastFCA绕过矩阵求逆和矩阵乘法。此外，FastFCA严格等同于传统算法。一项实验表明，FastFCA的速度比传统算法快250倍，具有几乎相同的源分离性能。

##### URL
[http://arxiv.org/abs/1805.06572](http://arxiv.org/abs/1805.06572)

##### PDF
[http://arxiv.org/pdf/1805.06572](http://arxiv.org/pdf/1805.06572)

