---
layout: post
title: "Fisher Pruning of Deep Nets for Facial Trait Classification"
date: 2018-11-18 01:20:41
categories: arXiv_CV
tags: arXiv_CV CNN Classification Deep_Learning Relation
author: Qing Tian, Tal Arbel, James J. Clark
mathjax: true
---

* content
{:toc}

##### Abstract
With deep learning's success, popular deep net structures are adopted for various vision tasks, which usually results in prohibitively high complexities for inclusion on devices without high-end GPUs. In this paper, we introduce a task-dependent neuron/filter level pruning framework based on Fisher's LDA. The approach can be applied to convolutional, fully-connected, and module-based deep structures, in all cases leveraging the high decorrelation of neuron motifs found in the pre-decision layer and cross-layer deconv dependency. Moreover, we examine our approach's potential in network architecture design given a specific task (e.g. facial trait classification). Experimental results on a wide array of facial traits from the LFWA and Adience datasets illustrate the framework's superior performance to state-of-the-art pruning approaches and fixed compact structures (e.g. SqueezeNet, MobileNet). We successfully maintained comparable accuracies even after discarding most parameters (98%-99% for VGG-16, 82% for GoogLeNet) and with significant FLOP reductions (83% for VGG-16, 64% for GoogLeNet). During pruning, we could also derive smaller, but more accurate, models suitable for the task.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1803.08134](http://arxiv.org/abs/1803.08134)

##### PDF
[http://arxiv.org/pdf/1803.08134](http://arxiv.org/pdf/1803.08134)

