---
layout: post
title: "Approximate FPGA-based LSTMs under Computation Time Constraints"
date: 2018-01-07 13:46:03
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption RNN Quantitative
author: Michalis Rizakis, Stylianos I. Venieris, Alexandros Kouris, Christos-Savvas Bouganis
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent Neural Networks and in particular Long Short-Term Memory (LSTM) networks have demonstrated state-of-the-art accuracy in several emerging Artificial Intelligence tasks. However, the models are becoming increasingly demanding in terms of computational and memory load. Emerging latency-sensitive applications including mobile robots and autonomous vehicles often operate under stringent computation time constraints. In this paper, we address the challenge of deploying computationally demanding LSTMs at a constrained time budget by introducing an approximate computing scheme that combines iterative low-rank compression and pruning, along with a novel FPGA-based LSTM architecture. Combined in an end-to-end framework, the approximation method's parameters are optimised and the architecture is configured to address the problem of high-performance LSTM execution in time-constrained applications. Quantitative evaluation on a real-life image captioning application indicates that the proposed methods required up to 6.5x less time to achieve the same application-level accuracy compared to a baseline method, while achieving an average of 25x higher accuracy under the same computation time constraints.

##### Abstract (translated by Google)
递归神经网络，尤其是长时间短期记忆（LSTM）网络已经在几个新兴的人工智能任务中展现了最新的精确度。但是，这些模型在计算和内存负载方面的要求越来越高。新兴的延迟敏感型应用，包括移动机器人和自主车辆，通常在严格的计算时间限制下运行。在本文中，我们通过引入结合迭代低秩压缩和修剪的近似计算方案，以及基于FPGA的新型LSTM架构，来解决在有限时间预算下部署计算要求较高的LSTM的挑战。结合端到端框架，对近似方法的参数进行优化，并配置架构以解决时间受限应用中高性能LSTM执行的问题。对实际图像字幕应用的定量评估表明，与基准方法相比，所提出的方法需要多达6.5倍的时间来实现相同的应用级精度，而在相同的计算时间约束下实现平均25倍的高精度。

##### URL
[http://arxiv.org/abs/1801.02190](http://arxiv.org/abs/1801.02190)

##### PDF
[http://arxiv.org/pdf/1801.02190](http://arxiv.org/pdf/1801.02190)

