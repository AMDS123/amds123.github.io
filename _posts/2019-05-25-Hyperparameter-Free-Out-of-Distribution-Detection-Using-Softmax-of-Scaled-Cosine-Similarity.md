---
layout: post
title: "Hyperparameter-Free Out-of-Distribution Detection Using Softmax of Scaled Cosine Similarity"
date: 2019-05-25 16:33:38
categories: arXiv_CV
tags: arXiv_CV Detection
author: Engkarat Techapanurak, Takayuki Okatani
mathjax: true
---

* content
{:toc}

##### Abstract
The ability of detecting out-of-distribution (OOD) samples is important to secure reliability of deep neural networks in real-world applications. Considering the nature of OOD samples, detection methods should not have hyperparameters whose optimal values vary sensitively depending on incoming OOD samples. This requirement is not met by many previous methods. In this paper, we propose a simple, hyperparameter-free method that is based on softmax of scaled cosine similarity. It resembles the approach employed by recent metric learning methods, but it differs in details; the differences are essential to achieve high detection performance. As compared with the current state-of-the-art methods, which needs hyperparameter tuning that could compromise real-world performance, the proposed method attains at least competitive detection accuracy even without (tuning of) a hyperparameter; furthermore, it is computationally more efficient, since it needs only a single forward pass unlike previous methods that need backpropagation for each input.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.10628](http://arxiv.org/abs/1905.10628)

##### PDF
[http://arxiv.org/pdf/1905.10628](http://arxiv.org/pdf/1905.10628)

