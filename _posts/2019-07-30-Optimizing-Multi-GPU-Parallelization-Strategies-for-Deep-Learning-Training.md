---
layout: post
title: "Optimizing Multi-GPU Parallelization Strategies for Deep Learning Training"
date: 2019-07-30 23:20:50
categories: arXiv_AI
tags: arXiv_AI NMT RNN Deep_Learning
author: Saptadeep Pal, Eiman Ebrahimi, Arslan Zulfiqar, Yaosheng Fu, Victor Zhang, Szymon Migacz, David Nellans, Puneet Gupta
mathjax: true
---

* content
{:toc}

##### Abstract
Deploying deep learning (DL) models across multiple compute devices to train large and complex models continues to grow in importance because of the demand for faster and more frequent training. Data parallelism (DP) is the most widely used parallelization strategy, but as the number of devices in data parallel training grows, so does the communication overhead between devices. Additionally, a larger aggregate batch size per step leads to statistical efficiency loss, i.e., a larger number of epochs are required to converge to a desired accuracy. These factors affect overall training time and beyond a certain number of devices, the speedup from leveraging DP begins to scale poorly. In addition to DP, each training step can be accelerated by exploiting model parallelism (MP). This work explores hybrid parallelization, where each data parallel worker is comprised of more than one device, across which the model dataflow graph (DFG) is split using MP. We show that at scale, hybrid training will be more effective at minimizing end-to-end training time than exploiting DP alone. We project that for Inception-V3, GNMT, and BigLSTM, the hybrid strategy provides an end-to-end training speedup of at least 26.5%, 8%, and 22% respectively compared to what DP alone can achieve at scale.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.13257](http://arxiv.org/abs/1907.13257)

##### PDF
[http://arxiv.org/pdf/1907.13257](http://arxiv.org/pdf/1907.13257)

