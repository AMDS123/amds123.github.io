---
layout: post
title: "Learning Features with Differentiable Closed-Form Solver for Tracking"
date: 2019-06-25 09:40:37
categories: arXiv_CV
tags: arXiv_CV Tracking Embedding CNN Deep_Learning
author: Linyu Zheng, Ming Tang, JinqiaoWang, Hanqing Lu
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel and easy-to-implement training framework for visual tracking. Our approach mainly focuses on learning feature embeddings in an end-to-end way, which can generalize well to the trackers based on online discriminatively trained ridge regression model. This goal is efficiently achieved by taking advantage of the following two important theories. 1) Ridge regression problem has closed-form solution and is implicit differentiation under the optimality condition. Therefore, its solver can be embedded as a layer with efficient forward and backward processes in training deep convolutional neural networks. 2) Woodbury identity can be utilized to ensure efficient solution of ridge regression problem when the high-dimensional feature embeddings are employed. Moreover, in order to address the extreme foreground-background class imbalance during training, we modify the origin shrinkage loss and then employ it as the loss function for efficient and effective training. It is worth mentioning that the above core parts of our proposed training framework are easy to be implemented with several lines of code under the current popular deep learning frameworks, thus our approach is easy to be followed. Extensive experiments on six public benchmarks, OTB2015, NFS, TrackingNet, GOT10k, VOT2018, and VOT2019, show that the proposed tracker achieves state-of-the-art performance, while running at over 30 FPS. Code will be made available.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.10414](http://arxiv.org/abs/1906.10414)

##### PDF
[http://arxiv.org/pdf/1906.10414](http://arxiv.org/pdf/1906.10414)

