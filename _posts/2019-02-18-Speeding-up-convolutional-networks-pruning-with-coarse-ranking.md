---
layout: post
title: "Speeding up convolutional networks pruning with coarse ranking"
date: 2019-02-18 03:13:16
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Zi Wang, Chengcheng Li, Dali Wang, Xiangyang Wang, Hairong Qi
mathjax: true
---

* content
{:toc}

##### Abstract
Channel-based pruning has achieved significant successes in accelerating deep convolutional neural network, whose pipeline is an iterative three-step procedure: ranking, pruning and fine-tuning. However, this iterative procedure is computationally expensive. In this study, we present a novel computationally efficient channel pruning approach based on the coarse ranking that utilizes the intermediate results during fine-tuning to rank the importance of filters, built upon state-of-the-art works with data-driven ranking criteria. The goal of this work is not to propose a single improved approach built upon a specific channel pruning method, but to introduce a new general framework that works for a series of channel pruning methods. Various benchmark image datasets (CIFAR-10, ImageNet, Birds-200, and Flowers-102) and network architectures (AlexNet and VGG-16) are utilized to evaluate the proposed approach for object classification purpose. Experimental results show that the proposed method can achieve almost identical performance with the corresponding state-of-the-art works (baseline) while our ranking time is negligibly short. In specific, with the proposed method, 75% and 54% of the total computation time for the whole pruning procedure can be reduced for AlexNet on CIFAR-10, and for VGG-16 on ImageNet, respectively. Our approach would significantly facilitate pruning practice, especially on resource-constrained platforms.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.06385](http://arxiv.org/abs/1902.06385)

##### PDF
[http://arxiv.org/pdf/1902.06385](http://arxiv.org/pdf/1902.06385)

