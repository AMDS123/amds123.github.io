---
layout: post
title: "Momentum-Net: Fast and convergent iterative neural network for inverse problems"
date: 2019-07-26 23:42:37
categories: arXiv_CV
tags: arXiv_CV Regularization Sparse Attention Optimization
author: Il Yong Chun, Zhengyu Huang, Hongki Lim, Jeffrey A. Fessler
mathjax: true
---

* content
{:toc}

##### Abstract
Iterative neural networks (INN) are rapidly gaining attention for solving inverse problems in imaging, image processing, and computer vision. INNs combine regression NNs and an iterative model-based image reconstruction (MBIR) algorithm, leading to both good generalization capability and outperforming reconstruction quality over existing MBIR optimization models. This paper proposes the first fast and convergent INN architecture, Momentum-Net, by generalizing a block-wise MBIR algorithm that uses momentums and majorizers with regression NNs. For fast MBIR, Momentum-Net uses momentum terms in extrapolation modules, and noniterative MBIR modules at each layer by using majorizers, where each layer of Momentum-Net consists of three core modules: image refining, extrapolation, and MBIR. Momentum-Net guarantees convergence to a fixed-point for general differentiable (non)convex MBIR functions (or data-fit terms) and convex feasible sets, under two asymptomatic conditions. To consider data-fit variations across training and testing samples, we also propose a regularization parameter selection scheme based on the spectral radius of majorization matrices. Numerical experiments for light-field photography using a focal stack and sparse-view computational tomography demonstrate that given identical regression NN architectures, Momentum-Net significantly improves MBIR speed and accuracy over several existing INNs; it significantly improves reconstruction quality compared to a state-of-the-art MBIR method in each application.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.11818](http://arxiv.org/abs/1907.11818)

##### PDF
[http://arxiv.org/pdf/1907.11818](http://arxiv.org/pdf/1907.11818)

