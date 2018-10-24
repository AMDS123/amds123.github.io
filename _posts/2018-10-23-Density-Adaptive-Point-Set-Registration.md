---
layout: post
title: "Density Adaptive Point Set Registration"
date: 2018-10-23 08:48:09
categories: arXiv_CV
tags: arXiv_CV
author: Felix J&#xe4;remo Lawin, Martin Danelljan, Fahad Shahbaz Khan, Per-Erik Forss&#xe9;n, Michael Felsberg
mathjax: true
---

* content
{:toc}

##### Abstract
Probabilistic methods for point set registration have demonstrated competitive results in recent years. These techniques estimate a probability distribution model of the point clouds. While such a representation has shown promise, it is highly sensitive to variations in the density of 3D points. This fundamental problem is primarily caused by changes in the sensor location across point sets. We revisit the foundations of the probabilistic registration paradigm. Contrary to previous works, we model the underlying structure of the scene as a latent probability distribution, and thereby induce invariance to point set density changes. Both the probabilistic model of the scene and the registration parameters are inferred by minimizing the Kullback-Leibler divergence in an Expectation Maximization based framework. Our density-adaptive registration successfully handles severe density variations commonly encountered in terrestrial Lidar applications. We perform extensive experiments on several challenging real-world Lidar datasets. The results demonstrate that our approach outperforms state-of-the-art probabilistic methods for multi-view registration, without the need of re-sampling. Code is available at https://github.com/felja633/DARE.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1804.01495](http://arxiv.org/abs/1804.01495)

##### PDF
[http://arxiv.org/pdf/1804.01495](http://arxiv.org/pdf/1804.01495)

