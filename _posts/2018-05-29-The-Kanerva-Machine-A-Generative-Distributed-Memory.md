---
layout: post
title: "The Kanerva Machine: A Generative Distributed Memory"
date: 2018-05-29 12:23:40
categories: arXiv_AI
tags: arXiv_AI Sparse
author: Yan Wu, Greg Wayne, Alex Graves, Timothy Lillicrap
mathjax: true
---

* content
{:toc}

##### Abstract
We present an end-to-end trained memory system that quickly adapts to new data and generates samples like them. Inspired by Kanerva's sparse distributed memory, it has a robust distributed reading and writing mechanism. The memory is analytically tractable, which enables optimal on-line compression via a Bayesian update-rule. We formulate it as a hierarchical conditional generative model, where memory provides a rich data-dependent prior distribution. Consequently, the top-down memory and bottom-up perception are combined to produce the code representing an observation. Empirically, we demonstrate that the adaptive memory significantly improves generative models trained on both the Omniglot and CIFAR datasets. Compared with the Differentiable Neural Computer (DNC) and its variants, our memory model has greater capacity and is significantly easier to train.

##### Abstract (translated by Google)
我们提供了一个端到端的训练有素的记忆系统，能够快速适应新数据并生成像他们这样的样本。受Kanerva稀疏分布式内存的启发，它具有强大的分布式读写机制。内存是易于分析的，可通过贝叶斯更新规则实现最佳的在线压缩。我们将其制定为分层条件生成模型，其中内存提供了丰富的数据依赖的先验分布。因此，自上而下的记忆和自下而上的感知被结合起来产生代表观察的代码。经验上，我们证明适应性记忆显着改善了在Omniglot和CIFAR数据集上训练的生成模型。与可微分神经计算机（DNC）及其变体相比，我们的记忆模型具有更大的容量并且更容易训练。

##### URL
[http://arxiv.org/abs/1804.01756](http://arxiv.org/abs/1804.01756)

##### PDF
[http://arxiv.org/pdf/1804.01756](http://arxiv.org/pdf/1804.01756)

