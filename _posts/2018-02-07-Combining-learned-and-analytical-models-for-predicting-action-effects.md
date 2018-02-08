---
layout: post
title: "Combining learned and analytical models for predicting action effects"
date: 2018-02-07 10:34:48
categories: arXiv_RO
tags: arXiv_RO Prediction
author: Alina Kloss, Stefan Schaal, Jeannette Bohg
mathjax: true
---

* content
{:toc}

##### Abstract
One of the most basic skills a robot should possess is predicting the effect of physical interactions with objects in the environment. This enables optimal action selection to reach a certain goal state. Traditionally, dynamics are described by physics-based analytical models. These may however be very hard to find for complex problems or may rely on state representations that are hard to obtain from sensory data. More recently, we have seen learning approaches that can predict the effect of complex physical interactions directly from sensory input. However, it is an open question how far these models generalize beyond their training data. In this work, we investigate the advantages and limitations of neural network based learning approaches and show how analytical and learned models can be combined to leverage the best of both worlds. As physical interaction task, we use planar pushing, for which there exists a well-known analytical model and a large real-world dataset. We propose to use a neural network to convert raw sensory data into a suitable representation for the analytical model and compare this approach to using neural networks for both, perception and prediction. We performed a systematic evaluation of the proposed approach on a very large real-world dataset. We observed two main advantages of the hybrid architecture: Compared to a pure neural network, it significantly (i) reduces required training data and (ii) improves generalization to novel physical interaction.

##### Abstract (translated by Google)
机器人应具备的最基本的技能之一是预测物体与环境中的物体相互作用的效果。这使得最佳的动作选择达到某个目标状态。传统上，动力学是基于物理的分析模型描述的。然而，这些可能很难找到复杂的问题，或者可能依赖于很难从传感数据中获得的状态表示。最近，我们已经看到了可以直接从感官输入中预测复杂物理相互作用的影响的学习方法。然而，这些模型在训练数据之外还有多远，这是一个悬而未决的问题。在这项工作中，我们调查了基于神经网络的学习方法的优点和局限性，并展示如何将分析和学习模型结合起来，以充分利用两者的优点。作为物理交互任务，我们使用平面推送，因为它存在一个众所周知的分析模型和一个大的现实世界的数据集。我们建议使用神经网络将原始的感官数据转换成分析模型的合适表示，并将这种方法与使用神经网络进行感知和预测进行比较。我们在非常大的真实世界的数据集上对所提出的方法进行了系统的评估。我们观察到了混合架构的两个主要优点：与纯粹的神经网络相比，它显着地（i）减少了所需的训练数据，并且（ii）改善了对新的物理交互的泛化。

##### URL
[http://arxiv.org/abs/1710.04102](http://arxiv.org/abs/1710.04102)

##### PDF
[http://arxiv.org/pdf/1710.04102](http://arxiv.org/pdf/1710.04102)

