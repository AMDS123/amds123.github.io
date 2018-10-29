---
layout: post
title: "Outlier Detection using Generative Models with Theoretical Performance Guarantees"
date: 2018-10-26 14:11:04
categories: arXiv_CV
tags: arXiv_CV Adversarial Sparse GAN CNN Detection Gradient_Descent
author: Jirong Yi, Anh Duc Le, Tianming Wang, Xiaodong Wu, Weiyu Xu
mathjax: true
---

* content
{:toc}

##### Abstract
This paper considers the problem of recovering signals from compressed measurements contaminated with sparse outliers, which has arisen in many applications. In this paper, we propose a generative model neural network approach for reconstructing the ground truth signals under sparse outliers. We propose an iterative alternating direction method of multipliers (ADMM) algorithm for solving the outlier detection problem via $\ell_1$ norm minimization, and a gradient descent algorithm for solving the outlier detection problem via squared $\ell_1$ norm minimization. We establish the recovery guarantees for reconstruction of signals using generative models in the presence of outliers, and give an upper bound on the number of outliers allowed for recovery. Our results are applicable to both the linear generator neural network and the nonlinear generator neural network with an arbitrary number of layers. We conduct extensive experiments using variational auto-encoder and deep convolutional generative adversarial networks, and the experimental results show that the signals can be successfully reconstructed under outliers using our approach. Our approach outperforms the traditional Lasso and $\ell_2$ minimization approach.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.11335](http://arxiv.org/abs/1810.11335)

##### PDF
[http://arxiv.org/pdf/1810.11335](http://arxiv.org/pdf/1810.11335)

