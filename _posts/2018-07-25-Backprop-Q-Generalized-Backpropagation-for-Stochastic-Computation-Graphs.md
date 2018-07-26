---
layout: post
title: "Backprop-Q: Generalized Backpropagation for Stochastic Computation Graphs"
date: 2018-07-25 10:06:24
categories: arXiv_AI
tags: arXiv_AI Review Reinforcement_Learning
author: Xiaoran Xu, Songpeng Zu, Hanning Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
In real-world scenarios, it is appealing to learn a model carrying out stochastic operations internally, known as stochastic computation graphs (SCGs), rather than learning a deterministic mapping. However, standard backpropagation is not applicable to SCGs. We attempt to address this issue from the angle of cost propagation, with local surrogate costs, called Q-functions, constructed and learned for each stochastic node in an SCG. Then, the SCG can be trained based on these surrogate costs using standard backpropagation. We propose the entire framework as a solution to generalize backpropagation for SCGs, which resembles an actor-critic architecture but based on a graph. For broad applicability, we study a variety of SCG structures from one cost to multiple costs. We utilize recent advances in reinforcement learning (RL) and variational Bayes (VB), such as off-policy critic learning and unbiased-and-low-variance gradient estimation, and review them in the context of SCGs. The generalized backpropagation extends transported learning signals beyond gradients between stochastic nodes while preserving the benefit of backpropagating gradients through deterministic nodes. Experimental suggestions and concerns are listed to help design and test any specific model using this framework.

##### Abstract (translated by Google)
在现实世界的情景中，学习在内部执行随机运算的模型（称为随机计算图（SCG））而不是学习确定性映射是有吸引力的。但是，标准反向传播不适用于SCG。我们试图从成本传播的角度解决这个问题，为SCG中的每个随机节点构建和学习称为Q函数的局部代理成本。然后，可以使用标准反向传播基于这些替代成本来训练SCG。我们提出整个框架作为一种解决方案来推广SCG的反向传播，它类似于演员评论体系结构，但基于图形。为了广泛的适用性，我们研究了从一种成本到多种成本的各种SCG结构。我们利用强化学习（RL）和变分贝叶斯（VB）的最新进展，例如非政策性批评学习和无偏和低方差梯度估计，并在SCG的背景下进行审查。广义反向传播将传输的学习信号扩展到随机节点之间的梯度之外，同时保留通过确定性节点反向传播梯度的益处。列出了实验建议和关注点，以帮助使用此框架设计和测试任何特定模型。

##### URL
[http://arxiv.org/abs/1807.09511](http://arxiv.org/abs/1807.09511)

##### PDF
[http://arxiv.org/pdf/1807.09511](http://arxiv.org/pdf/1807.09511)

