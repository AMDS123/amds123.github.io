---
layout: post
title: "Measuring Catastrophic Forgetting in Neural Networks"
date: 2017-11-09 14:53:07
categories: arXiv_CV
tags: arXiv_CV Regularization Sparse Classification Recognition
author: Ronald Kemker, Marc McClure, Angelina Abitino, Tyler Hayes, Christopher Kanan
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks are used in many state-of-the-art systems for machine perception. Once a network is trained to do a specific task, e.g., bird classification, it cannot easily be trained to do new tasks, e.g., incrementally learning to recognize additional bird species or learning an entirely different task such as flower recognition. When new tasks are added, typical deep neural networks are prone to catastrophically forgetting previous tasks. Networks that are capable of assimilating new information incrementally, much like how humans form new memories over time, will be more efficient than re-training the model from scratch each time a new task needs to be learned. There have been multiple attempts to develop schemes that mitigate catastrophic forgetting, but these methods have not been directly compared, the tests used to evaluate them vary considerably, and these methods have only been evaluated on small-scale problems (e.g., MNIST). In this paper, we introduce new metrics and benchmarks for directly comparing five different mechanisms designed to mitigate catastrophic forgetting in neural networks: regularization, ensembling, rehearsal, dual-memory, and sparse-coding. Our experiments on real-world images and sounds show that the mechanism(s) that are critical for optimal performance vary based on the incremental training paradigm and type of data being used, but they all demonstrate that the catastrophic forgetting problem has yet to be solved.

##### Abstract (translated by Google)
深度神经网络被用于许多最先进的机器感知系统。一旦网络被训练来执行特定的任务，例如鸟类分类，就不容易被训练成做新的任务，例如逐渐地学习识别另外的鸟种或学习完全不同的任务，例如花识别。当添加新的任务时，典型的深度神经网络容易灾难性地忘记以前的任务。能够逐步吸收新信息的网络，就像人类如何随着时间的推移形成新的记忆一样，比每次需要学习新任务时从头开始重新训练模型更有效率。已经有多种尝试来开发减轻灾难性遗忘的方案，但是这些方法没有直接比较，用于评估它们的测试变化很大，而且这些方法只是在小规模问题上进行评估（如MNIST）。在本文中，我们引入了新的指标和基准，直接比较五种不同的机制，旨在减轻神经网络中的灾难性遗忘：正则化，合成，排练，双存储器和稀疏编码。我们对真实世界的图像和声音的实验表明，对于最佳性能至关重要的机制是基于增量训练范式和所使用的数据类型而变化的，但是它们都证明了灾难性遗忘问题尚未解决。

##### URL
[https://arxiv.org/abs/1708.02072](https://arxiv.org/abs/1708.02072)

##### PDF
[https://arxiv.org/pdf/1708.02072](https://arxiv.org/pdf/1708.02072)

