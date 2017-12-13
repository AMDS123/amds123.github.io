---
layout: post
title: "Learning Time/Memory-Efficient Deep Architectures with Budgeted Super Networks"
date: 2017-11-27 09:09:34
categories: arXiv_CV
tags: arXiv_CV Prediction Gradient_Descent
author: Tom Veniat, Ludovic Denoyer
mathjax: true
---

* content
{:toc}

##### Abstract
We propose to focus on the problem of discovering neural network architectures efficient both in terms of prediction quality and cost. For instance, our approach is able to solve the following tasks: 'learn a neural network able to predict well in less than 100 milliseconds' or 'learn an efficient model that fits in a 50 Mb memory'. Our contribution is a novel family of models called Budgeted Super Networks. They are learned using gradient descent techniques applied on a budgeted learning objective function which integrates a maximum authorized cost where this cost can be of different nature. We present a set of experiments on computer vision problems and analyze the ability of our technique to deal with three different costs: the computation cost, the memory consumption cost, and also a \textit{distributed computation} cost. We particularly show that our model can discover neural network architectures that have a better accuracy than the ResNet and CNF architectures on CIFAR-10 and CIFAR-100, at a lower cost.

##### Abstract (translated by Google)
我们提出关注在预测质量和成本方面发现神经网络结构的问题。例如，我们的方法能够解决以下任务：“学习一个能够在100毫秒内完成预测的神经网络”或者“学习一个适合50 Mb内存的高效模型”。我们的贡献是一个称为预算超级网络的新型模型家族。他们学习使用梯度下降技术应用于预算学习目标函数，该函数集成了最大的授权成本，其中该成本可以是不同的性质。我们提出了一组关于计算机视觉问题的实验，并分析了我们的技术处理三种不同成本的能力：计算成本，内存消耗成本和分配计算成本。我们特别表明，我们的模型可以发现比CIFAR-10和CIFAR-100上的ResNet和CNF架构更精确的神经网络架构，成本更低。

##### URL
[https://arxiv.org/abs/1706.00046](https://arxiv.org/abs/1706.00046)

##### PDF
[https://arxiv.org/pdf/1706.00046](https://arxiv.org/pdf/1706.00046)

