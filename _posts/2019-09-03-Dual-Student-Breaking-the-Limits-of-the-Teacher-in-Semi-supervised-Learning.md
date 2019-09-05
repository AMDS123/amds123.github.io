---
layout: post
title: "Dual Student: Breaking the Limits of the Teacher in Semi-supervised Learning"
date: 2019-09-03 17:32:11
categories: arXiv_CV
tags: arXiv_CV Classification Prediction
author: Zhanghan Ke, Daoye Wang, Qiong Yan, Jimmy Ren, Rynson W.H. Lau
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, consistency-based methods have achieved state-of-the-art results in semi-supervised learning (SSL). These methods always involve two roles, an explicit or implicit teacher model and a student model, and penalize predictions under different perturbations by a consistency constraint. However, the weights of these two roles are tightly coupled since the teacher is essentially an exponential moving average (EMA) of the student. In this work, we show that the coupled EMA teacher causes a performance bottleneck. To address this problem, we introduce Dual Student, which replaces the teacher with another student. We also define a novel concept, stable sample, following which a stabilization constraint is designed for our structure to be trainable. Further, we discuss two variants of our method, which produce even higher performance. Extensive experiments show that our method improves the classification performance significantly on several main SSL benchmarks. Specifically, it reduces the error rate of the 13-layer CNN from 16.84% to 12.39% on CIFAR-10 with 1k labels and from 34.10% to 31.56% on CIFAR-100 with 10k labels. In addition, our method also achieves a clear improvement in domain adaptation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.01804](http://arxiv.org/abs/1909.01804)

##### PDF
[http://arxiv.org/pdf/1909.01804](http://arxiv.org/pdf/1909.01804)

