---
layout: post
title: "Dual Skew Divergence Loss for Neural Machine Translation"
date: 2019-08-22 14:16:20
categories: arXiv_CL
tags: arXiv_CL NMT Prediction
author: Fengshun Xiao, Yingting Wu, Hai Zhao, Rui Wang, Shu Jiang
mathjax: true
---

* content
{:toc}

##### Abstract
For neural sequence model training, maximum likelihood (ML) has been commonly adopted to optimize model parameters with respect to the corresponding objective. However, in the case of sequence prediction tasks like neural machine translation (NMT), training with the ML-based cross entropy loss would often lead to models that overgeneralize and plunge into local optima. In this paper, we propose an extended loss function called dual skew divergence (DSD), which aims to give a better tradeoff between generalization ability and error avoidance during NMT training. Our empirical study indicates that switching to DSD loss after the convergence of ML training helps the model skip the local optimum and stimulates a stable performance improvement. The evaluations on WMT 2014 English-German and English-French translation tasks demonstrate that the proposed loss indeed helps bring about better translation performance than several baselines.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.08399](https://arxiv.org/abs/1908.08399)

##### PDF
[https://arxiv.org/pdf/1908.08399](https://arxiv.org/pdf/1908.08399)

