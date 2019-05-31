---
layout: post
title: "Generalized Separable Nonnegative Matrix Factorization"
date: 2019-05-30 12:18:25
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Junjun Pan, Nicolas Gillis
mathjax: true
---

* content
{:toc}

##### Abstract
Nonnegative matrix factorization (NMF) is a linear dimensionality technique for nonnegative data with applications such as image analysis, text mining, audio source separation and hyperspectral unmixing. Given a data matrix $M$ and a factorization rank $r$, NMF looks for a nonnegative matrix $W$ with $r$ columns and a nonnegative matrix $H$ with $r$ rows such that $M \approx WH$. NMF is NP-hard to solve in general. However, it can be computed efficiently under the separability assumption which requires that the basis vectors appear as data points, that is, that there exists an index set $\mathcal{K}$ such that $W = M(:,\mathcal{K})$. In this paper, we generalize the separability assumption: We only require that for each rank-one factor $W(:,k)H(k,:)$ for $k=1,2,\dots,r$, either $W(:,k) = M(:,j)$ for some $j$ or $H(k,:) = M(i,:)$ for some $i$. We refer to the corresponding problem as generalized separable NMF (GS-NMF). We discuss some properties of GS-NMF and propose a convex optimization model which we solve using a fast gradient method. We also propose a heuristic algorithm inspired by the successive projection algorithm. To verify the effectiveness of our methods, we compare them with several state-of-the-art separable NMF algorithms on synthetic, document and image data sets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.12995](http://arxiv.org/abs/1905.12995)

##### PDF
[http://arxiv.org/pdf/1905.12995](http://arxiv.org/pdf/1905.12995)

