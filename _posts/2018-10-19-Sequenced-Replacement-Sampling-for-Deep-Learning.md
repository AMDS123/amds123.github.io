---
layout: post
title: "Sequenced-Replacement Sampling for Deep Learning"
date: 2018-10-19 00:55:47
categories: arXiv_CV
tags: arXiv_CV Classification Deep_Learning
author: Chiu Man Ho, Dae Hoon Park, Wei Yang, Yi Chang
mathjax: true
---

* content
{:toc}

##### Abstract
We propose sequenced-replacement sampling (SRS) for training deep neural networks. The basic idea is to assign a fixed sequence index to each sample in the dataset. Once a mini-batch is randomly drawn in each training iteration, we refill the original dataset by successively adding samples according to their sequence index. Thus we carry out replacement sampling but in a batched and sequenced way. In a sense, SRS could be viewed as a way of performing "mini-batch augmentation". It is particularly useful for a task where we have a relatively small images-per-class such as CIFAR-100. Together with a longer period of initial large learning rate, it significantly improves the classification accuracy in CIFAR-100 over the current state-of-the-art results. Our experiments indicate that training deeper networks with SRS is less prone to over-fitting. In the best case, we achieve an error rate as low as 10.10%.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.08322](http://arxiv.org/abs/1810.08322)

##### PDF
[http://arxiv.org/pdf/1810.08322](http://arxiv.org/pdf/1810.08322)

