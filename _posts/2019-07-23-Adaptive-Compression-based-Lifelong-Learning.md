---
layout: post
title: "Adaptive Compression-based Lifelong Learning"
date: 2019-07-23 04:58:52
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Optimization Classification Deep_Learning
author: Shivangi Srivastava, Maxim Berman, Matthew B. Blaschko, Devis Tuia
mathjax: true
---

* content
{:toc}

##### Abstract
The problem of a deep learning model losing performance on a previously learned task when fine-tuned to a new one is a phenomenon known as Catastrophic forgetting. There are two major ways to mitigate this problem: either preserving activations of the initial network during training with a new task; or restricting the new network activations to remain close to the initial ones. The latter approach falls under the denomination of lifelong learning, where the model is updated in a way that it performs well on both old and new tasks, without having access to the old task's training samples anymore. Recently, approaches like pruning networks for freeing network capacity during sequential learning of tasks have been gaining in popularity. Such approaches allow learning small networks while making redundant parameters available for the next tasks. The common problem encountered with these approaches is that the pruning percentage is hard-coded, irrespective of the number of samples, of the complexity of the learning task and of the number of classes in the dataset. We propose a method based on Bayesian optimization to perform adaptive compression/pruning of the network and show its effectiveness in lifelong learning. Our method learns to perform heavy pruning for small and/or simple datasets while using milder compression rates for large and/or complex data. Experiments on classification and semantic segmentation demonstrate the applicability of learning network compression, where we are able to effectively preserve performances along sequences of tasks of varying complexity.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.09695](http://arxiv.org/abs/1907.09695)

##### PDF
[http://arxiv.org/pdf/1907.09695](http://arxiv.org/pdf/1907.09695)

