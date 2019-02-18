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


##### URL
[http://arxiv.org/abs/1509.00296](http://arxiv.org/abs/1509.00296)

##### PDF
[http://arxiv.org/pdf/1509.00296](http://arxiv.org/pdf/1509.00296)

