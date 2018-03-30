---
layout: post
title: "Fisher Pruning of Deep Nets for Facial Trait Classification"
date: 2018-03-21 20:52:32
categories: arXiv_CV
tags: arXiv_CV CNN Classification Relation
author: Qing Tian, Tal Arbel, James J. Clark
mathjax: true
---

* content
{:toc}

##### Abstract
Although deep nets have resulted in high accuracies for various visual tasks, their computational and space requirements are prohibitively high for inclusion on devices without high-end GPUs. In this paper, we introduce a neuron/filter level pruning framework based on Fisher's LDA which leads to high accuracies for a wide array of facial trait classification tasks, while significantly reducing space/computational complexities. The approach is general and can be applied to convolutional, fully-connected, and module-based deep structures, in all cases leveraging the high decorrelation of neuron activations found in the pre-decision layer and cross-layer deconv dependency. Experimental results on binary and multi-category facial traits from the LFWA and Adience datasets illustrate the framework's comparable/better performance to state-of-the-art pruning approaches and compact structures (e.g. SqueezeNet, MobileNet). Ours successfully maintains comparable accuracies even after discarding most parameters (98%-99% for VGG-16, 82% for GoogLeNet) and with significant FLOP reductions (83% for VGG-16, 64% for GoogLeNet).

##### Abstract (translated by Google)
尽管深层网络导致了各种视觉任务的高精度，但对于没有高端GPU的设备而言，其计算和空间要求高得惊人。在本文中，我们介绍了一个基于Fisher的LDA的神经元/滤波器级修剪框架，该框架可以为各种面部特征分类任务提供高精度，同时显着减少空间/计算复杂性。该方法是通用的，可应用于卷积，完全连接和基于模块的深层结构，在所有情况下均可利用预决策层中发现的神经元激活的高度去相关性和跨层去卷积相关性。对来自LFWA和Adience数据集的二元和多类别面部特征的实验结果表明，该框架与最先进的修剪方法和紧凑结构（例如SqueezeNet，MobileNet）相比/更好的性能。即使放弃了大部分参数（VGG-16为98％-99％，GoogLeNet为82％），FLOP降低幅度为83％（VGG-16为64％，GoogLeNet为64％），我们仍能成功保持可比较的精度。

##### URL
[https://arxiv.org/abs/1803.08134](https://arxiv.org/abs/1803.08134)

##### PDF
[https://arxiv.org/pdf/1803.08134](https://arxiv.org/pdf/1803.08134)

