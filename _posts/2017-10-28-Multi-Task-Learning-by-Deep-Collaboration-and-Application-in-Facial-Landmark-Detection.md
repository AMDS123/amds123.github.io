---
layout: post
title: "Multi-Task Learning by Deep Collaboration and Application in Facial Landmark Detection"
date: 2017-10-28 03:51:16
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Deep_Learning Detection
author: Ludovic Trottier, Philippe Giguère, Brahim Chaib-draa
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks (CNN) have become the most successful and popular approach in many vision-related domains. While CNNs are particularly well-suited for capturing a proper hierarchy of concepts from real-world images, they are limited to domains where data is abundant. Recent attempts have looked into mitigating this data scarcity problem by casting their original single-task problem into a new multi-task learning (MTL) problem. The main goal of this inductive transfer mechanism is to leverage domain-specific information from related tasks, in order to improve generalization on the main task. While recent results in the deep learning (DL) community have shown the promising potential of training task-specific CNNs in a soft parameter sharing framework, integrating the recent DL advances for improving knowledge sharing is still an open problem. In this paper, we propose the Deep Collaboration Network (DCNet), a novel approach for connecting task-specific CNNs in a MTL framework. We define connectivity in terms of two distinct non-linear transformations. One aggregates task-specific features into global features, while the other merges back the global features with each task-specific network. Based on the observation that task relevance depends on depth, our transformations use skip connections as suggested by residual networks, to more easily deactivate unrelated task-dependent features. To validate our approach, we employ facial landmark detection (FLD) datasets as they are readily amenable to MTL, given the number of tasks they include. Experimental results show that we can achieve up to 24.31% relative improvement in failure rate over other state-of-the-art MTL approaches. We finally perform an ablation study showing that our approach effectively allows knowledge sharing, by leveraging domain-specific features at particular depths from tasks that we know are related.

##### Abstract (translated by Google)
卷积神经网络（CNN）已经成为许多视觉相关领域中最成功和流行的方法。虽然CNN特别适合从真实世界的图像中捕捉适当的概念层次，但是它们仅限于数据丰富的领域。最近的尝试已经考虑通过将其原始的单任务问题投入到新的多任务学习（MTL）问题中来缓解这个数据稀缺问题。这个归纳转移机制的主要目标是利用来自相关任务的领域特定信息，以改进对主要任务的概括。尽管深度学习（DL）社区的近期成果已经显示出在软参数共享框架中训练任务特定的CNN的潜力，但是将DL最近的进展与改进知识共享结合起来仍然是一个悬而未决的问题。在本文中，我们提出深层协作网络（DCNet），这是一种用于在MTL框架中连接任务特定CNN的新方法。我们用两个不同的非线性变换来定义连通性。一个将特定于任务的功能聚合到全局功能中，另一个将全局功能与每个特定于任务的网络合并。基于任务相关性依赖于深度的观察，我们的转换使用如残余网络所建议的跳过连接，以更容易地去激活不相关的任务相关特征。为了验证我们的方法，我们使用面部标志检测（FLD）数据集，因为它们很容易接受MTL，因为它们包含的任务数量很多。实验结果表明，与其他最先进的MTL方法相比，我们可以实现高达24.31％的故障率相对提高。我们最终进行消融研究，表明我们的方法通过利用我们所知道的相关任务的特定深度的特定领域特征来有效地实现知识共享。

##### URL
[https://arxiv.org/abs/1711.00111](https://arxiv.org/abs/1711.00111)

##### PDF
[https://arxiv.org/pdf/1711.00111](https://arxiv.org/pdf/1711.00111)

