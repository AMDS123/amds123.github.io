---
layout: post
title: "Robust Point Cloud Based Reconstruction of Large-Scale Outdoor Scenes"
date: 2019-05-23 13:10:21
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Ziquan Lan, Zi Jian Yew, Gim Hee Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Outlier feature matches and loop-closures that survived front-end data association can lead to catastrophic failures in the back-end optimization of large-scale point cloud based 3D reconstruction. To alleviate this problem, we propose a probabilistic approach for robust back-end optimization in the presence of outliers. More specifically, we model the problem as a Bayesian network and solve it using the Expectation-Maximization algorithm. Our approach leverages on a long-tail Cauchy distribution to suppress outlier feature matches in the odometry constraints, and a Cauchy-Uniform mixture model with a set of binary latent variables to simultaneously suppress outlier loop-closure constraints and outlier feature matches in the inlier loop-closure constraints. Furthermore, we show that by using a Gaussian-Uniform mixture model, our approach degenerates to the formulation of a state-of-the-art approach for robust indoor reconstruction. Experimental results demonstrate that our approach has comparable performance with the state-of-the-art on a benchmark indoor dataset, and outperforms it on a large-scale outdoor dataset. Our source code can be found on the project website.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.09634](http://arxiv.org/abs/1905.09634)

##### PDF
[http://arxiv.org/pdf/1905.09634](http://arxiv.org/pdf/1905.09634)

