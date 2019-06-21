---
layout: post
title: "AccUDNN: A GPU Memory Efficient Accelerator for Training Ultra-deep Neural Networks"
date: 2019-06-20 10:19:32
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Jinrong Guo, Wantao Liu, Wang Wang, Qu Lu, Songlin Hu, Jizhong Han, Ruixuan Li
mathjax: true
---

* content
{:toc}

##### Abstract
Typically, Ultra-deep neural network(UDNN) tends to yield high-quality model, but its training process is usually resource intensive and time-consuming. Modern GPU's scarce DRAM capacity is the primary bottleneck that hinders the trainability and the training efficiency of UDNN. In this paper, we present "AccUDNN", an accelerator that aims to make the utmost use of finite GPU memory resources to speed up the training process of UDNN. AccUDNN mainly includes two modules: memory optimizer and hyperparameter tuner. Memory optimizer develops a performance-model guided dynamic swap out/in strategy, by offloading appropriate data to host memory, GPU memory footprint can be significantly slashed to overcome the restriction of trainability of UDNN. After applying the memory optimization strategy, hyperparameter tuner is designed to explore the efficiency-optimal minibatch size and the matched learning rate. Evaluations demonstrate that AccUDNN cuts down the GPU memory requirement of ResNet-152 from more than 24GB to 8GB. In turn, given 12GB GPU memory budget, the efficiency-optimal minibatch size can reach 4.2x larger than original Caffe. Benefiting from better utilization of single GPU's computing resources and fewer parameter synchronization of large minibatch size, 7.7x speed-up is achieved by 8 GPUs' cluster without any communication optimization and no accuracy losses.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.06773](http://arxiv.org/abs/1901.06773)

##### PDF
[http://arxiv.org/pdf/1901.06773](http://arxiv.org/pdf/1901.06773)

