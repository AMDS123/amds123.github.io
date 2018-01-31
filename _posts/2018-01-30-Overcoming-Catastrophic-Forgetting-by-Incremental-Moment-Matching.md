---
layout: post
title: "Overcoming Catastrophic Forgetting by Incremental Moment Matching"
date: 2018-01-30 05:01:28
categories: arXiv_AI
tags: arXiv_AI Transfer_Learning
author: Sang-Woo Lee, Jin-Hwa Kim, Jaehyun Jun, Jung-Woo Ha, Byoung-Tak Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Catastrophic forgetting is a problem of neural networks that loses the information of the first task after training the second task. Here, we propose a method, i.e. incremental moment matching (IMM), to resolve this problem. IMM incrementally matches the moment of the posterior distribution of the neural network which is trained on the first and the second task, respectively. To make the search space of posterior parameter smooth, the IMM procedure is complemented by various transfer learning techniques including weight transfer, L2-norm of the old and the new parameter, and a variant of dropout with the old parameter. We analyze our approach on a variety of datasets including the MNIST, CIFAR-10, Caltech-UCSD-Birds, and Lifelog datasets. The experimental results show that IMM achieves state-of-the-art performance by balancing the information between an old and a new network.

##### Abstract (translated by Google)
灾难性遗忘是训练第二项任务后丢失第一项任务信息的神经网络问题。在这里，我们提出一种方法，即增量力矩匹配（IMM）来解决这个问题。 IMM分别递增地匹配在第一和第二任务上训练的神经网络的后验分布的时刻。为了使后验参数的搜索空间平滑，IMM程序由各种传递学习技术（包括权重转移，新旧参数的L2范数，以及旧参数丢失的变体）补充。我们在包括MNIST，CIFAR-10，Caltech-UCSD-Birds和Lifelog数据集在内的各种数据集上分析了我们的方法。实验结果表明，IMM通过平衡旧网络和新网络之间的信息来实现最先进的性能。

##### URL
[http://arxiv.org/abs/1703.08475](http://arxiv.org/abs/1703.08475)

##### PDF
[http://arxiv.org/pdf/1703.08475](http://arxiv.org/pdf/1703.08475)

