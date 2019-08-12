---
layout: post
title: "On the Variance of the Adaptive Learning Rate and Beyond"
date: 2019-08-08 20:51:17
categories: arXiv_CL
tags: arXiv_CL Image_Classification Optimization Classification Language_Model
author: Liyuan Liu, Haoming Jiang, Pengcheng He, Weizhu Chen, Xiaodong Liu, Jianfeng Gao, Jiawei Han
mathjax: true
---

* content
{:toc}

##### Abstract
The learning rate warmup heuristic achieves remarkable success in stabilizing training, accelerating convergence and improving generalization for adaptive stochastic optimization algorithms like RMSprop and Adam. Here, we study its mechanism in details. Pursuing the theory behind warmup, we identify a problem of the adaptive learning rate (i.e., it has problematically large variance in the early stage), suggest warmup works as a variance reduction technique, and provide both empirical and theoretical evidence to verify our hypothesis. We further propose RAdam, a new variant of Adam, by introducing a term to rectify the variance of the adaptive learning rate. Extensive experimental results on image classification, language modeling, and neural machine translation verify our intuition and demonstrate the effectiveness and robustness of our proposed method. All implementations are available at: this https URL.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.03265](https://arxiv.org/abs/1908.03265)

##### PDF
[https://arxiv.org/pdf/1908.03265](https://arxiv.org/pdf/1908.03265)

