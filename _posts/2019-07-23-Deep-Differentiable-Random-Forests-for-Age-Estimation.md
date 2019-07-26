---
layout: post
title: "Deep Differentiable Random Forests for Age Estimation"
date: 2019-07-23 02:44:38
categories: arXiv_CV
tags: arXiv_CV CNN
author: Wei Shen, Yilu Guo, Yan Wang, Kai Zhao, Bo Wang, Alan Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
Age estimation from facial images is typically cast as a label distribution learning or regression problem, since aging is a gradual progress. Its main challenge is the facial feature space w.r.t. ages is inhomogeneous, due to the large variation in facial appearance across different persons of the same age and the non-stationary property of aging. In this paper, we propose two Deep Differentiable Random Forests methods, Deep Label Distribution Learning Forest (DLDLF) and Deep Regression Forest (DRF), for age estimation. Both of them connect split nodes to the top layer of convolutional neural networks (CNNs) and deal with inhomogeneous data by jointly learning input-dependent data partitions at the split nodes and age distributions at the leaf nodes. This joint learning follows an alternating strategy: (1) Fixing the leaf nodes and optimizing the split nodes and the CNN parameters by Back-propagation; (2) Fixing the split nodes and optimizing the leaf nodes by Variational Bounding. Two Deterministic Annealing processes are introduced into the learning of the split and leaf nodes, respectively, to avoid poor local optima and obtain better estimates of tree parameters free of initial values. Experimental results show that DLDLF and DRF achieve state-of-the-art performance on three age estimation datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.10665](http://arxiv.org/abs/1907.10665)

##### PDF
[http://arxiv.org/pdf/1907.10665](http://arxiv.org/pdf/1907.10665)

