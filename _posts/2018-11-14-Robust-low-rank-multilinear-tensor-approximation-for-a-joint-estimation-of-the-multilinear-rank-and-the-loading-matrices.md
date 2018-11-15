---
layout: post
title: "Robust low-rank multilinear tensor approximation for a joint estimation of the multilinear rank and the loading matrices"
date: 2018-11-14 15:46:34
categories: arXiv_CV
tags: arXiv_CV
author: Xu Han, Laurent Albera, Amar Kachenoura, Huazhong Shu, Lotfi Senhadji
mathjax: true
---

* content
{:toc}

##### Abstract
In order to compute the best low-rank tensor approximation using the Multilinear Tensor Decomposition (MTD) model, it is essential to estimate the rank of the underlying multilinear tensor from the noisy observation tensor. In this paper, we propose a Robust MTD (R-MTD) method, which jointly estimates the multilinear rank and the loading matrices. Based on the low-rank property and an over-estimation of the core tensor, this joint estimation problem is solved by promoting (group) sparsity of the over-estimated core tensor. Group sparsity is promoted using mixed-norms. Then we establish a link between the mixed-norms and the nuclear norm, showing that mixed-norms are better candidates for a convex envelope of the rank. After several iterations of the Alternating Direction Method of Multipliers (ADMM), the Minimum Description Length (MDL) criterion computed from the eigenvalues of the unfolding matrices of the estimated core tensor is minimized in order to estimate the multilinear rank. The latter is then used to estimate more accurately the loading matrices. We further develop another R-MTD method, called R-OMTD, by imposing an orthonormality constraint on each loading matrix in order to decrease the computation complexity. A series of simulated noisy tensor and real-world data are used to show the effectiveness of the proposed methods compared with state-of-the-art methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.05863](http://arxiv.org/abs/1811.05863)

##### PDF
[http://arxiv.org/pdf/1811.05863](http://arxiv.org/pdf/1811.05863)

