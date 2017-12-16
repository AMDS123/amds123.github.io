---
layout: post
title: "Practical Network Blocks Design with Q-Learning"
date: 2017-08-18 10:12:43
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN
author: Zhao Zhong, Junjie Yan, Cheng-Lin Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural network provides an end-to-end solution to train many computer vision tasks and has gained great successes. However, the design of network architectures usually relies heavily on expert knowledge and is hand-crafted. In this paper, we provide a solution to automatically and efficiently design high performance network architectures. To reduce the search space of network design, we focus on constructing network blocks, which can be stacked to generate the whole network. Blocks are generated through an agent, which is trained with Q-learning to maximize the expected accuracy of the searching blocks on the learning task. Distributed asynchronous framework and early stop strategy are used to accelerate the training process. Our experimental results demonstrate that the network architectures designed by our approach perform competitively compared with hand-crafted state-of-the-art networks. We trained the Q-learning on CIFAR-100, and evaluated on CIFAR10 and ImageNet, the designed block structure achieved 3.60% error on CIFAR-10 and competitive result on ImageNet. The Q-learning process can be efficiently trained only on 32 GPUs in 3 days.

##### Abstract (translated by Google)
卷积神经网络为训练许多计算机视觉任务提供了一个端到端的解决方案，并取得了巨大的成功。然而，网络架构的设计通常严重依赖于专业知识，而且是手工制作的。在本文中，我们提供了一个自动和高效地设计高性能网络架构的解决方案。为了减少网络设计的搜索空间，我们着重构建网络块，将其堆叠起来生成整个网络。块通过代理来生成，该代理通过Q学习来训练，以最大化搜索块在学习任务上的预期精度。分布式异步框架和早期停止策略被用来加速训练过程。我们的实验结果表明，我们的方法设计的网络架构与手工制作的最先进的网络相比，具有竞争力。我们在CIFAR-100上进行了Q-learning的学习，并在CIFAR10和ImageNet上进行了评估，设计的块结构在CIFAR-10上达到了3.60％的误差，并在ImageNet上达到了较好的竞争效果。 Q学习过程可以在3天内仅在32个GPU上进行高效培训。

##### URL
[https://arxiv.org/abs/1708.05552](https://arxiv.org/abs/1708.05552)

##### PDF
[https://arxiv.org/pdf/1708.05552](https://arxiv.org/pdf/1708.05552)

