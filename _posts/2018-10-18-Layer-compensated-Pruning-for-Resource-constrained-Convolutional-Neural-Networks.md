---
layout: post
title: "Layer-compensated Pruning for Resource-constrained Convolutional Neural Networks"
date: 2018-10-18 02:36:01
categories: arXiv_CV
tags: arXiv_CV CNN Optimization
author: Ting-Wu Chin, Cha Zhang, Diana Marculescu
mathjax: true
---

* content
{:toc}

##### Abstract
Resource-efficient convolution neural networks enable not only the intelligence on edge devices but also opportunities in system-level optimization such as scheduling. In this work, we aim to improve the performance of resource-constrained filter pruning by merging two sub-problems commonly considered, i.e., (i) how many filters to prune for each layer and (ii) which filters to prune given a per-layer pruning budget, into a global filter ranking problem. Our framework entails a novel algorithm, dubbed layer-compensated pruning, where meta-learning is involved to determine better solutions. We show empirically that the proposed algorithm is superior to prior art in both effectiveness and efficiency. Specifically, we reduce the accuracy gap between the pruned and original networks from 0.9% to 0.7% with 8x reduction in time needed for meta-learning, i.e., from 1 hour down to 7 minutes. To this end, we demonstrate the effectiveness of our algorithm using ResNet and MobileNetV2 networks under CIFAR-10, ImageNet, and Bird-200 datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.00518](http://arxiv.org/abs/1810.00518)

##### PDF
[http://arxiv.org/pdf/1810.00518](http://arxiv.org/pdf/1810.00518)

