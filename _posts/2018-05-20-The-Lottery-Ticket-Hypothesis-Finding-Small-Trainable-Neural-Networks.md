---
layout: post
title: "The Lottery Ticket Hypothesis: Finding Small, Trainable Neural Networks"
date: 2018-05-20 19:46:47
categories: arXiv_AI
tags: arXiv_AI CNN Inference
author: Jonathan Frankle, Michael Carbin
mathjax: true
---

* content
{:toc}

##### Abstract
Neural network compression techniques are able to reduce the parameter counts of trained networks by over 90%--decreasing storage requirements and improving inference performance--without compromising accuracy. However, contemporary experience is that it is difficult to train small architectures from scratch, which would similarly improve training performance. 
 We articulate a new conjecture to explain why it is easier to train large networks: the "lottery ticket hypothesis." It states that large networks that train successfully contain subnetworks that--when trained in isolation--converge in a comparable number of iterations to comparable accuracy. These subnetworks, which we term "winning tickets," have won the initialization lottery: their connections have initial weights that make training particularly effective. 
 We find that a standard technique for pruning unnecessary network weights naturally uncovers a subnetwork which, at the start of training, comprised a winning ticket. We present an algorithm to identify winning tickets and a series of experiments that support the lottery ticket hypothesis. We consistently find winning tickets that are less than 20% of the size of several fully-connected, convolutional, and residual architectures for MNIST and CIFAR10. Furthermore, winning tickets at moderate levels of pruning (20-50% of the original network size) converge up to 6.7x faster than the original network and exhibit higher test accuracy.

##### Abstract (translated by Google)
神经网络压缩技术能够将训练网络的参数计数减少90％以上 - 降低存储要求并提高推理性能 - 同时不会降低准确性。然而，当代的经验是，难以从头开始培训小型架构，这同样会提高培训绩效。
 我们阐述了一个新的猜想，以解释为什么培训大型网络更容易：“彩票假设”。它指出，成功训练的大型网络包含的子网络 - 在孤立训练时 - 以相当的迭代次数收敛到可比较的精度。这些子网络，我们称之为“获奖门票”，赢得了初始化彩票：他们的联系具有初始权重，这使得培训特别有效。
 我们发现用于修剪不必要的网络权重的标准技术自然揭示了一个子网，在训练开始时，子网包括一张中奖票。我们提出一种算法来识别获奖彩票和一系列支持彩票假设的实验。我们始终如一地发现获奖门票少于几个MNIST和CIFAR10的完全连接，卷积和剩余体系结构大小的20％。此外，在中等修剪程度（原始网络尺寸的20-50％）中获胜的门票收敛速度比原始网络快6.7倍，并显示出更高的测试精度。

##### URL
[http://arxiv.org/abs/1803.03635](http://arxiv.org/abs/1803.03635)

##### PDF
[http://arxiv.org/pdf/1803.03635](http://arxiv.org/pdf/1803.03635)

