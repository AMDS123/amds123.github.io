---
layout: post
title: "AutoLoss: Learning Discrete Schedules for Alternate Optimization"
date: 2018-10-04 22:21:55
categories: arXiv_CL
tags: arXiv_CL GAN Optimization NMT Classification
author: Haowen Xu, Hao Zhang, Zhiting Hu, Xiaodan Liang, Ruslan Salakhutdinov, Eric Xing
mathjax: true
---

* content
{:toc}

##### Abstract
Many machine learning problems involve iteratively and alternately optimizing different task objectives with respect to different sets of parameters. Appropriately scheduling the optimization of a task objective or a set of parameters is usually crucial to the quality of convergence. In this paper, we present AutoLoss, a meta-learning framework that automatically learns and determines the optimization schedule. AutoLoss provides a generic way to represent and learn the discrete optimization schedule from metadata, allows for a dynamic and data-driven schedule in ML problems that involve alternating updates of different parameters or from different loss objectives. We apply AutoLoss on four ML tasks: d-ary quadratic regression, classification using a multi-layer perceptron (MLP), image generation using GANs, and multi-task neural machine translation (NMT). We show that the AutoLoss controller is able to capture the distribution of better optimization schedules that result in higher quality of convergence on all four tasks. The trained AutoLoss controller is generalizable -- it can guide and improve the learning of a new task model with different specifications, or on different datasets.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.02442](https://arxiv.org/abs/1810.02442)

##### PDF
[https://arxiv.org/pdf/1810.02442](https://arxiv.org/pdf/1810.02442)

