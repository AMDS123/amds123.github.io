---
layout: post
title: "Deep RNN Framework for Visual Sequential Applications"
date: 2018-11-25 06:34:29
categories: arXiv_CV
tags: arXiv_CV Video_Classification RNN Classification Prediction
author: Bo Pang, Kaiwen Zha, Hanwen Cao, Chen Shi, Cewu Lu
mathjax: true
---

* content
{:toc}

##### Abstract
Extracting temporal and representation features efficiently plays a pivotal role in understanding visual sequence information. To deal with this, we propose a new recurrent neural framework that can be stacked deep effectively. There are mainly two novel designs in our deep RNN framework: one is a new RNN module called Representation Bridge Module (RBM) which splits the information flowing along the sequence (temporal direction) and along depth (spatial representation direction), making it easier to train when building deep by balancing these two directions; the other is the Overlap Coherence Training Scheme that reduces the training complexity for long visual sequential tasks on account of the limitation of computing resources. We provide empirical evidence to show that our deep RNN framework is easy to optimize and can gain accuracy from the increased depth on several visual sequence problems. On these tasks, we evaluate our deep RNN framework with 15 layers, 7 times than conventional RNN networks, but it is still easy to train. Our deep framework achieves more than 11% relative improvements over shallow RNN models on Kinetics, UCF-101, and HMDB-51 for video classification. For auxiliary annotation, after replacing the shallow RNN part of Polygon-RNN with our 15-layer deep RBM, the performance improves by 14.7%. For video future prediction, our deep RNN improves the state-of-the-art shallow model's performance by 2.4% on PSNR and SSIM. The code and trained models will publish accompanied by this paper.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.09961](https://arxiv.org/abs/1811.09961)

##### PDF
[https://arxiv.org/pdf/1811.09961](https://arxiv.org/pdf/1811.09961)

