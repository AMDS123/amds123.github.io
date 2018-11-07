---
layout: post
title: "DiCE: The Infinitely Differentiable Monte-Carlo Estimator"
date: 2018-09-19 19:11:15
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Jakob Foerster, Gregory Farquhar, Maruan Al-Shedivat, Tim Rocktäschel, Eric P. Xing, Shimon Whiteson
mathjax: true
---

* content
{:toc}

##### Abstract
The score function estimator is widely used for estimating gradients of stochastic objectives in stochastic computation graphs (SCG), eg, in reinforcement learning and meta-learning. While deriving the first-order gradient estimators by differentiating a surrogate loss (SL) objective is computationally and conceptually simple, using the same approach for higher-order derivatives is more challenging. Firstly, analytically deriving and implementing such estimators is laborious and not compliant with automatic differentiation. Secondly, repeatedly applying SL to construct new objectives for each order derivative involves increasingly cumbersome graph manipulations. Lastly, to match the first-order gradient under differentiation, SL treats part of the cost as a fixed sample, which we show leads to missing and wrong terms for estimators of higher-order derivatives. To address all these shortcomings in a unified way, we introduce DiCE, which provides a single objective that can be differentiated repeatedly, generating correct estimators of derivatives of any order in SCGs. Unlike SL, DiCE relies on automatic differentiation for performing the requisite graph manipulations. We verify the correctness of DiCE both through a proof and numerical evaluation of the DiCE derivative estimates. We also use DiCE to propose and evaluate a novel approach for multi-agent learning. Our code is available at this https URL.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1802.05098](https://arxiv.org/abs/1802.05098)

##### PDF
[https://arxiv.org/pdf/1802.05098](https://arxiv.org/pdf/1802.05098)

