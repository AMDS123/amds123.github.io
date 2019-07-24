---
layout: post
title: "MemNet: Memory-Efficiency Guided Neural Architecture Search with Augment-Trim learning"
date: 2019-07-22 20:49:53
categories: arXiv_CV
tags: arXiv_CV Inference
author: Peiye Liu, Bo Wu, Huadong Ma, Pavan Kumar Chundi, Mingoo Seok
mathjax: true
---

* content
{:toc}

##### Abstract
Recent studies on automatic neural architectures search have demonstrated significant performance, competitive to or even better than hand-crafted neural architectures. However, most of the existing network architecture tend to use residual, parallel structures and concatenation block between shallow and deep features to construct a large network. This requires large amounts of memory for storing both weights and feature maps. This is challenging for mobile and embedded devices since they may not have enough memory to perform inference with the designed large network model. To close this gap, we propose MemNet, an augment-trim learning-based neural network search framework that optimizes not only performance but also memory requirement. Specifically, it employs memory consumption based ranking score which forces an upper bound on memory consumption for navigating the search process. Experiment results show that, as compared to the state-of-the-art efficient designing methods, MemNet can find an architecture which can achieve competitive accuracy and save an average of 24.17% on the total memory needed.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.09569](http://arxiv.org/abs/1907.09569)

##### PDF
[http://arxiv.org/pdf/1907.09569](http://arxiv.org/pdf/1907.09569)

