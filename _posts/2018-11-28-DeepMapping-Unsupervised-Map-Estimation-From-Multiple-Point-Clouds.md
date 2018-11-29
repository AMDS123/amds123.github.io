---
layout: post
title: "DeepMapping: Unsupervised Map Estimation From Multiple Point Clouds"
date: 2018-11-28 05:51:38
categories: arXiv_CV
tags: arXiv_CV Optimization Classification Quantitative SLAM
author: Li Ding, Chen Feng
mathjax: true
---

* content
{:toc}

##### Abstract
We propose DeepMapping, a novel registration framework using deep neural networks (DNNs) as auxiliary functions to align multiple point clouds from scratch to a globally consistent frame. We use DNNs to model the highly non-convex mapping process that traditionally involves hand-crafted data association, sensor pose initialization, and global refinement. Our key novelty is that properly defining unsupervised losses to "train" these DNNs through back-propagation is equivalent to solving the underlying registration problem, yet enables fewer dependencies on good initialization as required by ICP. Our framework contains two DNNs: a localization network that estimates the poses for input point clouds, and a map network that models the scene structure by estimating the occupancy status of global coordinates. This allows us to convert the registration problem to a binary occupancy classification, which can be solved efficiently using gradient-based optimization. We further show that DeepMapping can be readily extended to address the problem of Lidar SLAM by imposing geometric constraints between consecutive point clouds. Experiments are conducted on both simulated and real datasets. Qualitative and quantitative comparisons demonstrate that DeepMapping often enables more robust and accurate global registration of multiple point clouds than existing techniques. Our code is available at <a href="http://ai4ce.github.io/DeepMapping/.">this http URL</a>

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.11397](http://arxiv.org/abs/1811.11397)

##### PDF
[http://arxiv.org/pdf/1811.11397](http://arxiv.org/pdf/1811.11397)

