---
layout: post
title: "Predictive-Corrective Networks for Action Detection"
date: 2017-12-12 05:13:43
categories: arXiv_CV
tags: arXiv_CV Image_Caption Optimization RNN Prediction Detection
author: Achal Dave, Olga Russakovsky, Deva Ramanan
mathjax: true
---

* content
{:toc}

##### Abstract
While deep feature learning has revolutionized techniques for static-image understanding, the same does not quite hold for video processing. Architectures and optimization techniques used for video are largely based off those for static images, potentially underutilizing rich video information. In this work, we rethink both the underlying network architecture and the stochastic learning paradigm for temporal data. To do so, we draw inspiration from classic theory on linear dynamic systems for modeling time series. By extending such models to include nonlinear mappings, we derive a series of novel recurrent neural networks that sequentially make top-down predictions about the future and then correct those predictions with bottom-up observations. Predictive-corrective networks have a number of desirable properties: (1) they can adaptively focus computation on "surprising" frames where predictions require large corrections, (2) they simplify learning in that only "residual-like" corrective terms need to be learned over time and (3) they naturally decorrelate an input data stream in a hierarchical fashion, producing a more reliable signal for learning at each layer of a network. We provide an extensive analysis of our lightweight and interpretable framework, and demonstrate that our model is competitive with the two-stream network on three challenging datasets without the need for computationally expensive optical flow.

##### Abstract (translated by Google)
虽然深度特征学习已经彻底改变了静态图像理解的技术，但对于视频处理来说，这并不是很理想。用于视频的体系结构和优化技术在很大程度上基于静态图像，潜在地利用丰富的视频信息。在这项工作中，我们重新思考底层网络架构和时态数据的随机学习范式。为此，我们从线性动态系统的经典理论中为时间序列建模汲取灵感。通过扩展这种模型使其包含非线性映射，我们推导出一系列新颖的递归神经网络，它们按顺序对未来进行自上而下的预测，然后用自下而上的观测来修正这些预测。预测校正网络具有许多理想的特性：（1）它们可以自适应地将计算集中在预测需要大量校正的“令人惊讶的”帧上;（2）它们简化了学习，因为只需要学习“类似剩余”的校正项随着时间的推移和（3）它们自然地以分层方式去相关输入数据流，在网络的每一层产生更可靠的信号用于学习。我们对轻量级和可解释的框架进行了广泛的分析，并证明我们的模型在三个具有挑战性的数据集上与双流网络相竞争，而不需要计算昂贵的光流。

##### URL
[http://arxiv.org/abs/1704.03615](http://arxiv.org/abs/1704.03615)

##### PDF
[http://arxiv.org/pdf/1704.03615](http://arxiv.org/pdf/1704.03615)

