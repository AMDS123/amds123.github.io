---
layout: post
title: "Routing Networks: Adaptive Selection of Non-linear Functions for Multi-Task Learning"
date: 2017-11-03 17:07:51
categories: arXiv_CV
tags: arXiv_CV GAN Reinforcement_Learning CNN
author: Clemens Rosenbaum, Tim Klinger, Matthew Riemer
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-task learning (MTL) with neural networks leverages commonalities in tasks to improve performance, but often suffers from task interference which reduces transfer. To address this issue we introduce the routing network paradigm, a novel neural network unit and training algorithm. A routing network is a kind of self-organizing neural network consisting of two components: a router and a set of one or more function blocks. A function block may be any neural network - for example a fully-connected or a convolutional layer. Given an input the router makes a routing decision, choosing a function block to apply and passing the output back to the router recursively, terminating when the router decides to stop or a fixed recursion depth is reached. In this way the routing network dynamically composes different function blocks for each input. We employ a collaborative multi-agent reinforcement learning (MARL) approach to jointly train the router and function blocks. We evaluate our model on multi-task settings of the MNIST, mini-imagenet, and CIFAR-100 datasets. Our experiments demonstrate significant improvement in accuracy with sharper convergence over challenging joint training baselines for these tasks.

##### Abstract (translated by Google)
具有神经网络的多任务学习（MTL）利用任务的共同性来提高性能，但是经常遭受减少传输的任务干扰。为了解决这个问题，我们引入了路由网络范例，一种新型的神经网络单元和训练算法。路由网络是一种自组织神经网络，由两部分组成：路由器和一个或多个功能块。功能块可以是任何神经网络，例如全连接层或卷积层。给定一个输入，路由器做出一个路由决定，选择一个功能块来应用并递归地将输出传递回路由器，当路由器决定停止或达到固定的递归深度时终止。这样路由网络为每个输入动态地组成不同的功能块。我们采用协作多智能体强化学习（MARL）方法来联合训练路由器和功能块。我们在MNIST，mini-imagenet和CIFAR-100数据集的多任务设置上评估我们的模型。我们的实验表明，在这些任务的挑战性的联合训练基线上，更精确的收敛更加明显。

##### URL
[https://arxiv.org/abs/1711.01239](https://arxiv.org/abs/1711.01239)

##### PDF
[https://arxiv.org/pdf/1711.01239](https://arxiv.org/pdf/1711.01239)

