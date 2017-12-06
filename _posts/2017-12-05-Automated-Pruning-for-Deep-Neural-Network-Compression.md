---
layout: post
title: 'Automated Pruning for Deep Neural Network Compression'
date: 2017-12-05 15:58:44
categories: arXiv_CV
tags: arXiv_CV Recognition
author: Franco Manessi, Alessandro Rozza, Simone Bianco, Paolo Napoletano, Raimondo Schettini
---

* content
{:toc}

##### Abstract
In this work we present a method to improve the pruning step of the current state-of-the-art methodology to compress neural networks. The novelty of the proposed pruning technique is in its differentiability, which allows pruning to be performed during the backpropagation phase of the network training. This enables an end-to-end learning and strongly reduces the training time. The technique is based on a family of differentiable pruning functions and a new regularizer specifically designed to enforce pruning. The experimental results show that the joint optimization of both the thresholds and the network weights permits to reach a higher compression rate, reducing the number of weights of the pruned network by a further 14% to 33% with respect to the current state-of-the-art. Furthermore, we believe that this is the first study where the generalization capabilities in transfer learning tasks of the features extracted by a pruned network are analyzed. To achieve this goal, we show that the representations learned using the proposed pruning methodology maintain the same effectiveness and generality of those learned by the corresponding non-compressed network on a set of different recognition tasks.

##### Abstract (translated by Google)
在这项工作中，我们提出了一种方法来改善当前最先进的方法来压缩神经网络的修剪步骤。所提出的修剪技术的新颖性在于其可微性，其允许在网络训练的反向传播阶段期间进行修剪。这实现了端到端的学习，并大大减少了培训时间。该技术是基于一个可区分的修剪功能家族和专门设计用于强制修剪的新调节器。实验结果表明，阈值和网络权重的联合优化允许达到较高的压缩率，相对于目前的状态机，将修剪网络的权重数量进一步减少14％到33％艺术。此外，我们认为这是第一个分析了由修剪网络提取的特征的转移学习任务的泛化能力的研究。为了实现这个目标，我们证明了使用所提出的修剪方法学习的表示在一组不同的识别任务中保持了相应的非压缩网络所学习的那些相同的有效性和一般性。

##### URL
[https://arxiv.org/abs/1712.01721](https://arxiv.org/abs/1712.01721)

