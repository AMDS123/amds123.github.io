---
layout: post
title: "Joint Neural Architecture Search and Quantization"
date: 2018-11-23 10:58:46
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Yukang Chen, Gaofeng Meng, Qian Zhang, Xinbang Zhang, Liangchen Song, Shiming Xiang, Chunhong Pan
mathjax: true
---

* content
{:toc}

##### Abstract
Designing neural architectures is a fundamental step in deep learning applications. As a partner technique, model compression on neural networks has been widely investigated to gear the needs that the deep learning algorithms could be run with the limited computation resources on mobile devices. Currently, both the tasks of architecture design and model compression require expertise tricks and tedious trials. In this paper, we integrate these two tasks into one unified framework, which enables the joint architecture search with quantization (compression) policies for neural networks. This method is named JASQ. Here our goal is to automatically find a compact neural network model with high performance that is suitable for mobile devices. Technically, a multi-objective evolutionary search algorithm is introduced to search the models under the balance between model size and performance accuracy. In experiments, we find that our approach outperforms the methods that search only for architectures or only for quantization policies. 1) Specifically, given existing networks, our approach can provide them with learning-based quantization policies, and outperforms their 2 bits, 4 bits, 8 bits, and 16 bits counterparts. It can yield higher accuracies than the float models, for example, over 1.02% higher accuracy on MobileNet-v1. 2) What is more, under the balance between model size and performance accuracy, two models are obtained with joint search of architectures and quantization policies: a high-accuracy model and a small model, JASQNet and JASQNet-Small that achieves 2.97% error rate with 0.9 MB on CIFAR-10.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.09426](http://arxiv.org/abs/1811.09426)

##### PDF
[http://arxiv.org/pdf/1811.09426](http://arxiv.org/pdf/1811.09426)

