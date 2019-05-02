---
layout: post
title: "Task-specific Fisher Pruning of Deep Nets"
date: 2019-05-01 15:28:54
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning Relation
author: Qing Tian, Tal Arbel, James J. Clark
mathjax: true
---

* content
{:toc}

##### Abstract
With deep learning's success, a limited number of popular deep nets have been widely adopted for various vision tasks. However, this usually results in unnecessarily high complexities and possibly less useful features for the task. In this paper, we address this problem by introducing a task-dependent deep pruning framework based on Fisher's LDA. The approach can be applied to convolutional, fully-connected, and module-based deep network structures, in all cases leveraging the high decorrelation of neuron motifs found in the pre-decision layer and cross-layer deconv dependency. Moreover, we examine our approach's potential in the network architecture design for specific tasks. Experimental results on datasets of generic objects, as well as domain specific tasks (CIFAR100, Adience, and LFWA) illustrate our framework's superior performance over state-of-the-art pruning approaches and fixed compact nets (e.g. SqueezeNet, MobileNet). The proposed method successfully maintains comparable accuracies even after discarding most parameters (98%-99% for VGG16, up to 82% for the already compact GoogLeNet) and with significant FLOP reductions (83% for VGG16, up to 64% for GoogLeNet). Through pruning, we can also derive smaller, but more accurate, models suitable for the task.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1803.08134](http://arxiv.org/abs/1803.08134)

##### PDF
[http://arxiv.org/pdf/1803.08134](http://arxiv.org/pdf/1803.08134)

