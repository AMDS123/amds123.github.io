---
layout: post
title: "Two geometric input transformation methods for fast online reinforcement learning with neural nets"
date: 2018-05-18 23:35:14
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Embedding
author: Sina Ghiassian, Huizhen Yu, Banafsheh Rafiee, Richard S. Sutton
mathjax: true
---

* content
{:toc}

##### Abstract
We apply neural nets with ReLU gates in online reinforcement learning. Our goal is to train these networks in an incremental manner, without the computationally expensive experience replay. By studying how individual neural nodes behave in online training, we recognize that the global nature of ReLU gates can cause undesirable learning interference in each node's learning behavior. We propose reducing such interferences with two efficient input transformation methods that are geometric in nature and match well the geometric property of ReLU gates. The first one is tile coding, a classic binary encoding scheme originally designed for local generalization based on the topological structure of the input space. The second one (EmECS) is a new method we introduce; it is based on geometric properties of convex sets and topological embedding of the input space into the boundary of a convex set. We discuss the behavior of the network when it operates on the transformed inputs. We also compare it experimentally with some neural nets that do not use the same input transformations, and with the classic algorithm of tile coding plus a linear function approximator, and on several online reinforcement learning tasks, we show that the neural net with tile coding or EmECS can achieve not only faster learning but also more accurate approximations. Our results strongly suggest that geometric input transformation of this type can be effective for interference reduction and takes us a step closer to fully incremental reinforcement learning with neural nets.

##### Abstract (translated by Google)
我们将神经网络与ReLU门适用于在线强化学习。我们的目标是以递增的方式训练这些网络，而不需要重复计算昂贵的体验。通过研究单个神经节点在在线训练中的表现，我们认识到，ReLU门的全局性质会在每个节点的学习行为中导致不希望的学习干扰。我们提出用两种有效的输入变换方法来减少这种干扰，这些方法几乎是几何的，并且很好地匹配了ReLU门的几何特性。第一个是平铺编码，这是一种经典的二进制编码方案，最初是基于输入空间的拓扑结构而设计的。第二个（EmECS）是我们介绍的一种新方法;它基于凸集的几何性质和输入空间到凸集边界的拓扑嵌入。我们讨论网络在变换后的输入上的行为。我们还将它与一些不使用相同输入变换的神经网络进行了实验比较，并且使用经典的瓦片编码算法加上一个线性函数逼近器，以及几个在线强化学习任务，我们证明了带瓦片编码的神经网络EmECS不仅可以实现更快的学习速度，还可以实现更精确的近似值。我们的结果强烈表明，这种几何输入变换可以有效地减少干扰，并使我们更接近于使用神经网络进行全增量强化学习。

##### URL
[https://arxiv.org/abs/1805.07476](https://arxiv.org/abs/1805.07476)

##### PDF
[https://arxiv.org/pdf/1805.07476](https://arxiv.org/pdf/1805.07476)

