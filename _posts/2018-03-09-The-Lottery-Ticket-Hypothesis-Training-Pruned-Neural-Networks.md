---
layout: post
title: "The Lottery Ticket Hypothesis: Training Pruned Neural Networks"
date: 2018-03-09 18:51:28
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Jonathan Frankle, Michael Carbin
mathjax: true
---

* content
{:toc}

##### Abstract
Recent work on neural network pruning indicates that, at training time, neural networks need to be significantly larger in size than is necessary to represent the eventual functions that they learn. This paper articulates a new hypothesis to explain this phenomenon. This conjecture, which we term the "lottery ticket hypothesis," proposes that successful training depends on lucky random initialization of a smaller subcomponent of the network. Larger networks have more of these "lottery tickets," meaning they are more likely to luck out with a subcomponent initialized in a configuration amenable to successful optimization. 
 This paper conducts a series of experiments with XOR and MNIST that support the lottery ticket hypothesis. In particular, we identify these fortuitously-initialized subcomponents by pruning low-magnitude weights from trained networks. We then demonstrate that these subcomponents can be successfully retrained in isolation so long as the subnetworks are given the same initializations as they had at the beginning of the training process. Initialized as such, these small networks reliably converge successfully, often faster than the original network at the same level of accuracy. However, when these subcomponents are randomly reinitialized or rearranged, they perform worse than the original network. In other words, large networks that train successfully contain small subnetworks with initializations conducive to optimization. 
 The lottery ticket hypothesis and its connection to pruning are a step toward developing architectures, initializations, and training strategies that make it possible to solve the same problems with much smaller networks.

##### Abstract (translated by Google)
最近在神经网络修剪方面的工作表明，在训练时间，神经网络的尺寸必须大于表示他们学习的最终功能所需的尺寸。本文阐述了一个新的假设来解释这种现象。这种我们称之为“彩票假设”的猜想提出，成功的训练取决于网络中较小子组件的幸运随机初始化。更大的网络拥有更多的这些“彩票”，这意味着他们更有可能在配置中初始化子组件，从而成功进行优化。
 本文用XOR和MNIST进行了一系列支持彩票假说的实验。特别是，我们通过修剪来自训练网络的低量级权重来识别这些偶然初始化的子组件。然后我们证明，只要这些子网络在训练过程开始时就有相同的初始化，就可以孤立地对这些子组件进行成功的再训练。如此初始化，这些小型网络成功地可靠地收敛，通常以比原始网络更高的准确度水平进行收敛。但是，当这些子组件被随机重新初始化或重新安排时，它们比原始网络执行得更差。换句话说，成功训练的大型网络包含有助于优化的初始化的小型子网。
 彩票假设及其与修剪的联系是朝着开发架构，初始化和培训策略迈出的一步，这些架构，初始化和培训策略可以解决与小型网络相同的问题。

##### URL
[http://arxiv.org/abs/1803.03635](http://arxiv.org/abs/1803.03635)

##### PDF
[http://arxiv.org/pdf/1803.03635](http://arxiv.org/pdf/1803.03635)

