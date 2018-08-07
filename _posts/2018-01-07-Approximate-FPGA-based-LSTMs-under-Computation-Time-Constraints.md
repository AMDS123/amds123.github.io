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
回归神经网络，特别是长短期记忆（LSTM）网络已经在几项新兴的人工智能任务中展示了最先进的准确性。然而，模型在计算和存储器负载方面变得越来越苛刻。新兴的对延迟敏感的应用程序（包括移动机器人和自动驾驶车辆）通常在严格的计算时间限制下运行在本文中，我们通过引入结合迭代低秩压缩和修剪的近似计算方案以及基于FPGA的新型LSTM架构，解决了在约束时间预算下部署计算要求苛刻的LSTM的挑战。结合在端到端框架中，近似方法的参数得到优化，架构配置为解决时间受限应用中高性能LSTM执行的问题。对现实生活中的图像字幕应用进行定量评估表明，与基线方法相比，所提出的方法需要的时间缩短6.5倍才能达到相同的应用级精度，同时在相同的计算时间限制下实现平均高出25倍的精度。

##### URL
[https://arxiv.org/abs/1801.02190](https://arxiv.org/abs/1801.02190)

##### PDF
[https://arxiv.org/pdf/1801.02190](https://arxiv.org/pdf/1801.02190)

