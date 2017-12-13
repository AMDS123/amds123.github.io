---
layout: post
title: "Hierarchical Memory Networks"
date: 2016-05-24 12:48:19
categories: arXiv_CV
tags: arXiv_CV Attention GAN Reinforcement_Learning Inference Memory_Networks
author: Sarath Chandar, Sungjin Ahn, Hugo Larochelle, Pascal Vincent, Gerald Tesauro, Yoshua Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
Memory networks are neural networks with an explicit memory component that can be both read and written to by the network. The memory is often addressed in a soft way using a softmax function, making end-to-end training with backpropagation possible. However, this is not computationally scalable for applications which require the network to read from extremely large memories. On the other hand, it is well known that hard attention mechanisms based on reinforcement learning are challenging to train successfully. In this paper, we explore a form of hierarchical memory network, which can be considered as a hybrid between hard and soft attention memory networks. The memory is organized in a hierarchical structure such that reading from it is done with less computation than soft attention over a flat memory, while also being easier to train than hard attention over a flat memory. Specifically, we propose to incorporate Maximum Inner Product Search (MIPS) in the training and inference procedures for our hierarchical memory network. We explore the use of various state-of-the art approximate MIPS techniques and report results on SimpleQuestions, a challenging large scale factoid question answering task.

##### Abstract (translated by Google)
内存网络是具有显式内存组件的神经网络，可以被网络读取和写入。内存通常使用softmax函数以柔和的方式解决，使得反向传播的端到端培训成为可能。然而，这对于需要网络从非常大的存储器中读取的应用来说不是可计算的可扩展的。另一方面，众所周知，基于强化学习的强调机制对培训的成功具有挑战性。在本文中，我们探讨了一种分层存储网络的形式，它可以被看作是硬性和软性记忆网络之间的混合。内存是按层次结构组织的，读取数据比使用平面内存的软件处理少，而且比平面内存更容易培训。具体而言，我们建议将最大内积搜索（MIPS）纳入我们分层存储网络的训练和推理程序中。我们探索使用各种最先进的近似MIPS技术，并在SimpleQuestions上进行结果报告，这是一个具有挑战性的大规模实际问题回答任务。

##### URL
[https://arxiv.org/abs/1605.07427](https://arxiv.org/abs/1605.07427)

##### PDF
[https://arxiv.org/pdf/1605.07427](https://arxiv.org/pdf/1605.07427)

