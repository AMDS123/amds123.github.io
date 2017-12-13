---
layout: post
title: "Cavs: A Vertex-centric Programming Interface for Dynamic Neural Networks"
date: 2017-12-11 22:04:39
categories: arXiv_CL
tags: arXiv_CL Face Optimization Deep_Learning
author: Hao Zhang, Shizhen Xu, Graham Neubig, Wei Dai, Qirong Ho, Guangwen Yang, Eric P. Xing
mathjax: true
---

* content
{:toc}

##### Abstract
Recent deep learning (DL) models have moved beyond static network architectures to dynamic ones, handling data where the network structure changes every example, such as sequences of variable lengths, trees, and graphs. Existing dataflow-based programming models for DL---both static and dynamic declaration---either cannot readily express these dynamic models, or are inefficient due to repeated dataflow graph construction and processing, and difficulties in batched execution. We present Cavs, a vertex-centric programming interface and optimized system implementation for dynamic DL models. Cavs represents dynamic network structure as a static vertex function $\mathcal{F}$ and a dynamic instance-specific graph $\mathcal{G}$, and performs backpropagation by scheduling the execution of $\mathcal{F}$ following the dependencies in $\mathcal{G}$. Cavs bypasses expensive graph construction and preprocessing overhead, allows for the use of static graph optimization techniques on pre-defined operations in $\mathcal{F}$, and naturally exposes batched execution opportunities over different graphs. Experiments comparing Cavs to two state-of-the-art frameworks for dynamic NNs (TensorFlow Fold and DyNet) demonstrate the efficacy of this approach: Cavs achieves a near one order of magnitude speedup on training of various dynamic NN architectures, and ablations demonstrate the contribution of our proposed batching and memory management strategies.

##### Abstract (translated by Google)
最近的深度学习（DL）模型已经超越了静态网络体系结构，变成了动态网络体系结构，处理网络结构在每个例子中变化的数据，例如可变长度，树和图的序列。用于DL的现有的基于数据流的编程模型 - 静态和动态声明 - 既不能容易地表达这些动态模型，或者由于重复的数据流图的构建和处理而效率低下，以及批量执行中的困难。我们提出了Cavs，一个以顶点为中心的编程接口，并为动态DL模型优化了系统实现。 Cavs将动态网络结构表示为一个静态顶点函数$ \ mathcal {F} $和一个动态特定于实例的图$ \ mathcal {G} $，并且通过调度$ \ mathcal {F} $的执行来执行反向传播在$ \ mathcal {G} $中。 Cavs绕过了昂贵的图形构建和预处理开销，允许在$ \ mathcal {F} $的预定义操作中使用静态图形优化技术，并自然地在不同的图形上显示批处理执行机会。将Cavs与动态神经网络（TensorFlowFold和DyNet）的两个现有技术框架进行比较的实验证明了这种方法的有效性：在各种动态NN体系结构的训练中，Cavs实现了接近一个数量级的加速，我们建议的配料和记忆管理战略的贡献。

##### URL
[http://arxiv.org/abs/1712.04048](http://arxiv.org/abs/1712.04048)

##### PDF
[http://arxiv.org/pdf/1712.04048](http://arxiv.org/pdf/1712.04048)

