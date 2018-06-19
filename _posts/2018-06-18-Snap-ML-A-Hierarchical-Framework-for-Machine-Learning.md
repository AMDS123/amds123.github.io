---
layout: post
title: "Snap ML: A Hierarchical Framework for Machine Learning"
date: 2018-06-18 11:30:36
categories: arXiv_AI
tags: arXiv_AI Review
author: Celestine D&#xfc;nner, Thomas Parnell, Dimitrios Sarigiannis, Nikolas Ioannou, Andreea Anghel, Haralampos Pozidis
mathjax: true
---

* content
{:toc}

##### Abstract
We describe a new software framework for fast training of generalized linear models. The framework, named Snap Machine Learning (Snap ML), combines recent advances in machine learning systems and algorithms in a nested manner to reflect the hierarchical architecture of modern computing systems. We prove theoretically that such a hierarchical system can accelerate training in distributed environments where intra-node communication is cheaper than inter-node communication. Additionally, we provide a review of the implementation of Snap ML in terms of GPU acceleration, pipelining, communication patterns and software architecture, highlighting aspects that were critical for achieving high performance. We evaluate the performance of Snap ML in both single-node and multi-node environments, quantifying the benefit of the hierarchical scheme and the data streaming functionality, and comparing with other widely-used machine learning software frameworks. Finally, we present a logistic regression benchmark on the Criteo Terabyte Click Logs dataset and show that Snap ML achieves the same test loss an order of magnitude faster than any of the previously reported results.

##### Abstract (translated by Google)
我们描述了用于快速训练广义线性模型的新软件框架。这个名为Snap Machine Learning（Snap ML）的框架将嵌入式机器学习系统和算法的最新进展结合起来，以反映现代计算系统的分层架构。我们在理论上证明，这样的分层系统可以加快分布式环境中的训练，其中节点内通信比节点间通信便宜。此外，我们还提供了Snap ML在GPU加速，流水线，通信模式和软件架构方面的实施情况回顾，突出了实现高性能至关重要的方面。我们评估Snap ML在单节点和多节点环境中的性能，量化分层方案和数据流功能的优点，并与其他广泛使用的机器学习软件框架进行比较。最后，我们在Criteo Terabyte Click Logs数据集上提供逻辑回归基准，并显示Snap ML实现的测试损失比之前报告的结果快一个数量级。

##### URL
[http://arxiv.org/abs/1803.06333](http://arxiv.org/abs/1803.06333)

##### PDF
[http://arxiv.org/pdf/1803.06333](http://arxiv.org/pdf/1803.06333)

