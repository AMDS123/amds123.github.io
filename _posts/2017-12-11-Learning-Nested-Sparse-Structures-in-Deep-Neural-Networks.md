---
layout: post
title: "Learning Nested Sparse Structures in Deep Neural Networks"
date: 2017-12-11 14:09:06
categories: arXiv_CV
tags: arXiv_CV Sparse Knowledge Inference Classification Deep_Learning
author: Eunwoo Kim, Chanho Ahn, Songhwai Oh
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, there have been increasing demands to construct compact deep architectures to remove unnecessary redundancy and to improve the inference speed. While many recent works focus on reducing the redundancy by eliminating unneeded weight parameters, it is not possible to apply a single deep architecture for multiple devices with different resources. When a new device or circumstantial condition requires a new deep architecture, it is necessary to construct and train a new network from scratch. In this work, we propose a novel deep learning framework, called a nested sparse network, which exploits an n-in-1-type nested structure in a neural network. A nested sparse network consists of multiple levels of networks with a different sparsity ratio associated with each level, and higher level networks share parameters with lower level networks to enable stable nested learning. The proposed framework realizes a resource-aware versatile architecture as the same network can meet diverse resource requirements. Moreover, the proposed nested network can learn different forms of knowledge in its internal networks at different levels, enabling multiple tasks using a single network, such as coarse-to-fine hierarchical classification. In order to train the proposed nested sparse network, we propose efficient weight connection learning and channel and layer scheduling strategies. We evaluate our network in multiple tasks, including adaptive deep compression, knowledge distillation, and learning class hierarchy, and demonstrate that nested sparse networks perform competitively, but more efficiently, than existing methods.

##### Abstract (translated by Google)
近来，构建紧凑的深层体系结构以消除不必要的冗余并提高推理速度的需求日益增加。虽然许多最近的工作集中在通过消除不必要的权重参数来减少冗余，但是不可能为具有不同资源的多个设备应用单个深度架构。当一个新的设备或情况条件需要一个新的深层架构时，有必要从头开始构建和培训一个新的网络。在这项工作中，我们提出了一个新的深度学习框架，称为嵌套稀疏网络，它利用神经网络中的一个n型嵌套结构。嵌套的稀疏网络由多级网络组成，每级网络具有不同的稀疏比率，上级网络与下级网络共享参数，实现稳定的嵌套学习。所提出的框架实现了资源感知的通用架构，因为同一个网络可以满足不同的资源需求。而且，所提出的嵌套网络可以在不同层次的内部网络中学习不同形式的知识，使得使用单一网络的多个任务成为可能，例如从粗到精的分层分类。为了训练提出的嵌套稀疏网络，我们提出了有效的权重连接学习和信道和层调度策略。我们评估我们的网络在多个任务，包括自适应深度压缩，知识蒸馏和学习类层次结构，并表明嵌套稀疏网络比现有方法竞争力，但更有效地执行。

##### URL
[http://arxiv.org/abs/1712.03781](http://arxiv.org/abs/1712.03781)

##### PDF
[http://arxiv.org/pdf/1712.03781](http://arxiv.org/pdf/1712.03781)

