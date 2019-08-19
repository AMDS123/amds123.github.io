---
layout: post
title: "ScarletNAS: Bridging the Gap Between Scalability and Fairness in Neural Architecture Search"
date: 2019-08-16 15:31:08
categories: arXiv_CV
tags: arXiv_CV
author: Xiangxiang Chu, Bo Zhang, Jixiang Li, Qingyuan Li, Ruijun Xu
mathjax: true
---

* content
{:toc}

##### Abstract
One-shot neural architecture search features fast training of a supernet in a single run. A pivotal issue for this weight-sharing approach is the lacking of scalability. A simple adjustment with identity block renders a scalable supernet but it arouses unstable training, which makes the subsequent model ranking unreliable. In this paper, we introduce linearly equivalent transformation to soothe training turbulence, providing with the proof that such transformed path is identical with the original one as per representational power. The overall method is named as SCARLET (SCAlable supeRnet with Linearly Equivalent Transformation). We show through experiments that linearly equivalent transformations can indeed harmonize the supernet training. With an EfficientNet-like search space and a multi-objective reinforced evolutionary backend, it generates a series of competitive models: Scarlet-A achieves 76.9% Top-1 accuracy on ImageNet which outperforms EfficientNet-B0 by a large margin; the shallower Scarlet-B exemplifies the proposed scalability which attains the same accuracy 76.3% as EfficientNet-B0 with much fewer FLOPs; Scarlet-C scores competitive 75.6% with comparable sizes. The models and evaluation code are released online this https URL .

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.06022](https://arxiv.org/abs/1908.06022)

##### PDF
[https://arxiv.org/pdf/1908.06022](https://arxiv.org/pdf/1908.06022)

