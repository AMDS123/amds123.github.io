---
layout: post
title: "Exploring Hyper-Parameter Optimization for Neural Machine Translation on GPU Architectures"
date: 2018-05-05 18:13:41
categories: arXiv_CL
tags: arXiv_CL Optimization NMT Deep_Learning Language_Model
author: Robert Lim, Kenneth Heafield, Hieu Hoang, Mark Briers, Allen Malony
mathjax: true
---

* content
{:toc}

##### Abstract
Neural machine translation (NMT) has been accelerated by deep learning neural networks over statistical-based approaches, due to the plethora and programmability of commodity heterogeneous computing architectures such as FPGAs and GPUs and the massive amount of training corpuses generated from news outlets, government agencies and social media. Training a learning classifier for neural networks entails tuning hyper-parameters that would yield the best performance. Unfortunately, the number of parameters for machine translation include discrete categories as well as continuous options, which makes for a combinatorial explosive problem. This research explores optimizing hyper-parameters when training deep learning neural networks for machine translation. Specifically, our work investigates training a language model with Marian NMT. Results compare NMT under various hyper-parameter settings across a variety of modern GPU architecture generations in single node and multi-node settings, revealing insights on which hyper-parameters matter most in terms of performance, such as words processed per second, convergence rates, and translation accuracy, and provides insights on how to best achieve high-performing NMT systems.

##### Abstract (translated by Google)
由于商品异构计算架构（如FPGA和GPU）的庞大程度和可编程性，以及来自新闻媒体，政府机构的大量训练语料库，神经机器翻译（NMT）已通过基于统计的方法深度学习神经网络加速和社交媒体。训练神经网络的学习分类器需要调整可以产生最佳性能的超参数。不幸的是，机器翻译的参数数量包括离散类别以及连续选项，这就导致了组合爆炸问题。本研究探讨了在机器翻译训练深度学习神经网络时优化超参数。具体来说，我们的工作是调查与玛丽安NMT培训语言模型。结果比较了在单个节点和多节点设置中，在各种现代GPU架构世代的各种超参数设置下的NMT，揭示了哪些超参数在性能方面最为重要，例如每秒处理的字数，收敛速率，和翻译准确性，并提供有关如何最佳实现高性能NMT系统的见解。

##### URL
[http://arxiv.org/abs/1805.02094](http://arxiv.org/abs/1805.02094)

##### PDF
[http://arxiv.org/pdf/1805.02094](http://arxiv.org/pdf/1805.02094)

