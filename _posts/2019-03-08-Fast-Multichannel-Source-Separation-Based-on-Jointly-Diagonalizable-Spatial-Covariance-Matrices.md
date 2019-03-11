---
layout: post
title: "Fast Multichannel Source Separation Based on Jointly Diagonalizable Spatial Covariance Matrices"
date: 2019-03-08 01:17:23
categories: arXiv_SD
tags: arXiv_SD
author: Kouhei Sekiguchi, Aditya Arie Nugraha, Yoshiaki Bando, Kazuyoshi Yoshii
mathjax: true
---

* content
{:toc}

##### Abstract
This paper describes a versatile method that accelerates multichannel source separation methods based on full-rank spatial modeling. A popular approach to multichannel source separation is to integrate a spatial model with a source model for estimating the spatial covariance matrices (SCMs) and power spectral densities (PSDs) of each sound source in the time-frequency domain. One of the most successful examples of this approach is multichannel nonnegative matrix factorization (MNMF) based on a full-rank spatial model and a low-rank source model. MNMF, however, is computationally expensive and often works poorly due to the difficulty of estimating the unconstrained full-rank SCMs. Instead of restricting the SCMs to rank-1 matrices with the severe loss of the spatial modeling ability as in independent low-rank matrix analysis (ILRMA), we restrict the SCMs of each frequency bin to jointly-diagonalizable but still full-rank matrices. For such a fast version of MNMF, we propose a computationally-efficient and convergence-guaranteed algorithm that is similar in form to that of ILRMA. Similarly, we propose a fast version of a state-of-the-art speech enhancement method based on a deep speech model and a low-rank noise model. Experimental results showed that the fast versions of MNMF and the deep speech enhancement method were several times faster and performed even better than the original versions of those methods, respectively.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.03237](http://arxiv.org/abs/1903.03237)

##### PDF
[http://arxiv.org/pdf/1903.03237](http://arxiv.org/pdf/1903.03237)

