---
layout: post
title: "Deep Bayesian Unsupervised Source Separation Based on a Complex Gaussian Mixture Model"
date: 2019-08-29 15:45:20
categories: arXiv_SD
tags: arXiv_SD
author: Yoshiaki Bando, Yoko Sasaki, Kazuyoshi Yoshii
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents an unsupervised method that trains neural source separation by using only multichannel mixture signals. Conventional neural separation methods require a lot of supervised data to achieve excellent performance. Although multichannel methods based on spatial information can work without such training data, they are often sensitive to parameter initialization and degraded with the sources located close to each other. The proposed method uses a cost function based on a spatial model called a complex Gaussian mixture model (cGMM). This model has the time-frequency (TF) masks and direction of arrivals (DoAs) of sources as latent variables and is used for training separation and localization networks that respectively estimate these variables. This joint training solves the frequency permutation ambiguity of the spatial model in a unified deep Bayesian framework. In addition, the pre-trained network can be used not only for conducting monaural separation but also for efficiently initializing a multichannel separation algorithm. Experimental results with simulated speech mixtures showed that our method outperformed a conventional initialization method.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.11307](http://arxiv.org/abs/1908.11307)

##### PDF
[http://arxiv.org/pdf/1908.11307](http://arxiv.org/pdf/1908.11307)

