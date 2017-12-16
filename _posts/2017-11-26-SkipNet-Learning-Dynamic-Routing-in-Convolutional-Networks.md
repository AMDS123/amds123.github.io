---
layout: post
title: "SkipNet: Learning Dynamic Routing in Convolutional Networks"
date: 2017-11-26 23:03:37
categories: arXiv_CV
tags: arXiv_CV Reinforcement_Learning CNN Inference
author: Xin Wang, Fisher Yu, Zi-Yi Dou, Joseph E. Gonzalez
mathjax: true
---

* content
{:toc}

##### Abstract
Increasing depth and complexity in convolutional neural networks has enabled significant progress in visual perception tasks. However, incremental improvements in accuracy are often accompanied by exponentially deeper models that push the computational limits of modern hardware. These incremental improvements in accuracy imply that only a small fraction of the inputs require the additional model complexity. As a consequence, for any given image it is possible to bypass multiple stages of computation to reduce the cost of forward inference without affecting accuracy. We exploit this simple observation by learning to dynamically route computation through a convolutional network. We introduce dynamically routed networks (SkipNets) by adding gating layers that route images through existing convolutional networks and formulate the routing problem in the context of sequential decision making. We propose a hybrid learning algorithm which combines supervised learning and reinforcement learning to address the challenges of inherently non-differentiable routing decisions. We show SkipNet reduces computation by 30 - 90% while preserving the accuracy of the original model on four benchmark datasets. We compare SkipNet with SACT and ACT to show SkipNet achieves better accuracy with lower computation.

##### Abstract (translated by Google)
卷积神经网络越来越深入和复杂化，使视觉感知任务取得了重大进展。然而，精度的逐渐提高通常伴随着指数级更深的模型，推动了现代硬件的计算极限。精度的这些逐渐提高意味着只有一小部分输入需要额外的模型复杂性。因此，对于任何给定的图像，可以绕过多个计算阶段来降低前向推理的成本而不影响准确性。我们利用这个简单的观察，学习通过卷积网络动态路由计算。我们通过增加门控层来引入动态路由网络（SkipNets），这些门控层通过现有的卷积网络路由图像，并且在顺序决策的背景下制定路由问题。我们提出了一个混合学习算法，结合监督学习和强化学习来解决固有的不可微分路由决策的挑战。我们显示SkipNet减少了30-90％的计算量，同时保留了原始模型在四个基准数据集上的准确性。我们将SkipNet与SACT和ACT进行比较，以显示SkipNet通过较低的计算达到更好的精度。

##### URL
[https://arxiv.org/abs/1711.09485](https://arxiv.org/abs/1711.09485)

##### PDF
[https://arxiv.org/pdf/1711.09485](https://arxiv.org/pdf/1711.09485)

