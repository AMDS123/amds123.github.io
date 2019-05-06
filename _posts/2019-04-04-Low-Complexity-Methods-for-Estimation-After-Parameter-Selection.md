---
layout: post
title: "Low-Complexity Methods for Estimation After Parameter Selection"
date: 2019-04-04 11:55:09
categories: arXiv_CV
tags: arXiv_CV Inference
author: Nadav Harel, Tirza Routtenberg
mathjax: true
---

* content
{:toc}

##### Abstract
Statistical inference of multiple parameters often involves a preliminary parameter selection stage. The selection stage has an impact on subsequent estimation, for example by introducing a selection bias. The post-selection maximum likelihood (PSML) estimator is shown to reduce the selection bias and the post-selection mean-squared-error (PSMSE) compared with conventional estimators, such as the maximum likelihood (ML) estimator. However, the computational complexity of the PSML is usually high due to the multi-dimensional exhaustive search for a global maximum of the post-selection log-likelihood (PSLL) function. Moreover, the PSLL involves the probability of selection that, in general, does not have an analytical form. In this paper, we develop new low-complexity post-selection estimation methods for a two-stage estimation after parameter selection architecture. The methods are based on implementing the iterative maximization by parts (MBP) approach, which is based on the decomposition of the PSLL function into "easily-optimized" and complicated parts. The proposed second-best PSML method, applies the MBP-PSML algorithm with a pairwise probability of selection between the two highest-ranked parameters w.r.t. the selection rule. The proposed SA-PSML method is based on using stochastic approximation (SA) and Monte Carlo integrations to obtain a non-parametric estimation of the gradient of the probability of selection and then applying the MBP-PSML algorithm on this approximation. For low-complexity performance analysis, we develop the empirical post-selection Cramer-Rao-type lower bound. Simulations demonstrate that the proposed post-selection estimation methods are tractable and reduce both the bias and the PSMSE, compared with the ML estimator, while only requiring moderate computational complexity.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1904.02500](https://arxiv.org/abs/1904.02500)

##### PDF
[https://arxiv.org/pdf/1904.02500](https://arxiv.org/pdf/1904.02500)

