---
layout: post
title: "SNIP: Single-shot Network Pruning based on Connection Sensitivity"
date: 2019-02-23 07:45:29
categories: arXiv_CV
tags: arXiv_CV Salient Sparse CNN Optimization Classification
author: Namhoon Lee, Thalaiyasingam Ajanthan, Philip H. S. Torr
mathjax: true
---

* content
{:toc}

##### Abstract
Pruning large neural networks while maintaining their performance is often desirable due to the reduced space and time complexity. In existing methods, pruning is done within an iterative optimization procedure with either heuristically designed pruning schedules or additional hyperparameters, undermining their utility. In this work, we present a new approach that prunes a given network once at initialization prior to training. To achieve this, we introduce a saliency criterion based on connection sensitivity that identifies structurally important connections in the network for the given task. This eliminates the need for both pretraining and the complex pruning schedule while making it robust to architecture variations. After pruning, the sparse network is trained in the standard way. Our method obtains extremely sparse networks with virtually the same accuracy as the reference network on the MNIST, CIFAR-10, and Tiny-ImageNet classification tasks and is broadly applicable to various architectures including convolutional, residual and recurrent networks. Unlike existing methods, our approach enables us to demonstrate that the retained connections are indeed relevant to the given task.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.02340](http://arxiv.org/abs/1810.02340)

##### PDF
[http://arxiv.org/pdf/1810.02340](http://arxiv.org/pdf/1810.02340)

