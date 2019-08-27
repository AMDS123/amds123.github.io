---
layout: post
title: "Confidence Regularized Self-Training"
date: 2019-08-26 17:56:13
categories: arXiv_CV
tags: arXiv_CV Regularization Segmentation Image_Classification Semantic_Segmentation Optimization Classification Prediction
author: Yang Zou, Zhiding Yu, Xiaofeng Liu, B. V. K. Vijaya Kumar, Jinsong Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advances in domain adaptation show that deep self-training presents a powerful means for unsupervised domain adaptation. These methods often involve an iterative process of predicting on target domain and then taking the confident predictions as pseudo-labels for retraining. However, since pseudo-labels can be noisy, self-training can put overconfident label belief on wrong classes, leading to deviated solutions with propagated errors. To address the problem, we propose a confidence regularized self-training (CRST) framework, formulated as regularized self-training. Our method treats pseudo-labels as continuous latent variables jointly optimized via alternating optimization. We propose two types of confidence regularization: label regularization (LR) and model regularization (MR). CRST-LR generates soft pseudo-labels while CRST-MR encourages the smoothness on network output. Extensive experiments on image classification and semantic segmentation show that CRSTs outperform their non-regularized counterpart with state-of-the-art performance. The code and models of this work are available at https://github.com/yzou2/CRST.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.09822](http://arxiv.org/abs/1908.09822)

##### PDF
[http://arxiv.org/pdf/1908.09822](http://arxiv.org/pdf/1908.09822)

