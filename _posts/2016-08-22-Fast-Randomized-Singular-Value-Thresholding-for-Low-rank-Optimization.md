---
layout: post
title: "Fast Randomized Singular Value Thresholding for Low-rank Optimization"
date: 2016-08-22 17:43:05
categories: arXiv_CV
tags: arXiv_CV Optimization Quantitative Relation
author: Tae-Hyun Oh, Yasuyuki Matsushita, Yu-Wing Tai, In So Kweon
mathjax: true
---

* content
{:toc}

##### Abstract
Rank minimization can be converted into tractable surrogate problems, such as Nuclear Norm Minimization (NNM) and Weighted NNM (WNNM). The problems related to NNM, or WNNM, can be solved iteratively by applying a closed-form proximal operator, called Singular Value Thresholding (SVT), or Weighted SVT, but they suffer from high computational cost of Singular Value Decomposition (SVD) at each iteration. We propose a fast and accurate approximation method for SVT, that we call fast randomized SVT (FRSVT), with which we avoid direct computation of SVD. The key idea is to extract an approximate basis for the range of the matrix from its compressed matrix. Given the basis, we compute partial singular values of the original matrix from the small factored matrix. In addition, by developping a range propagation method, our method further speeds up the extraction of approximate basis at each iteration. Our theoretical analysis shows the relationship between the approximation bound of SVD and its effect to NNM via SVT. Along with the analysis, our empirical results quantitatively and qualitatively show that our approximation rarely harms the convergence of the host algorithms. We assess the efficiency and accuracy of the proposed method on various computer vision problems, e.g., subspace clustering, weather artifact removal, and simultaneous multi-image alignment and rectification.

##### Abstract (translated by Google)
秩最小化可以转化为易处理的替代问题，例如核范数最小化（NNM）和加权NNM（WNNM）。与NNM或WNNM相关的问题可以通过应用称为奇异值阈值（SVT）或加权SVT的封闭形式的近端算子来迭代地求解，但是它们在每个时刻都遭受高的计算成本的奇异值分解（SVD）迭代。我们提出了一种快速而准确的SVT逼近方法，我们称之为快速随机SVT（FRSVT），避免了直接计算SVD。关键的思想是从其压缩矩阵中提取矩阵范围的近似基础。给定基础，我们从小分解矩阵中计算原始矩阵的部分奇异值。另外，通过开发距离传播方法，我们的方法在每次迭代中进一步加速提取近似基础。我们的理论分析表明了奇异值分解的逼近界与它通过SVT对NNM的影响之间的关系。随着分析，我们的实证结果定量和定性表明，我们的近似很少损害主机算法的收敛。我们评估所提出的方法在各种计算机视觉问题上的效率和准确度，例如，子空间聚类，天气伪像去除以及同时多图像对齐和校正。

##### URL
[https://arxiv.org/abs/1509.00296](https://arxiv.org/abs/1509.00296)

##### PDF
[https://arxiv.org/pdf/1509.00296](https://arxiv.org/pdf/1509.00296)

