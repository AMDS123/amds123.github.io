---
layout: post
title: "Labeled Memory Networks for Online Model Adaptation"
date: 2017-12-02 07:31:20
categories: arXiv_CV
tags: arXiv_CV GAN RNN Classification Memory_Networks
author: Shiv Shankar, Sunita Sarawagi
mathjax: true
---

* content
{:toc}

##### Abstract
Augmenting a neural network with memory that can grow without growing the number of trained parameters is a recent powerful concept with many exciting applications. We propose a design of memory augmented neural networks (MANNs) called Labeled Memory Networks (LMNs) suited for tasks requiring online adaptation in classification models. LMNs organize the memory with classes as the primary key.The memory acts as a second boosted stage following a regular neural network thereby allowing the memory and the primary network to play complementary roles. Unlike existing MANNs that write to memory for every instance and use LRU based memory replacement, LMNs write only for instances with non-zero loss and use label-based memory replacement. We demonstrate significant accuracy gains on various tasks including word-modelling and few-shot learning. In this paper, we establish their potential in online adapting a batch trained neural network to domain-relevant labeled data at deployment time. We show that LMNs are better than other MANNs designed for meta-learning. We also found them to be more accurate and faster than state-of-the-art methods of retuning model parameters for adapting to domain-specific labeled data.

##### Abstract (translated by Google)
在不增加训练参数的情况下增加一个可以增长的内存的神经网络是一个最近的强大的概念，有许多令人兴奋的应用。我们提出了一种称为标记记忆网络（LMNs）的记忆增强神经网络（MANNs）设计，适用于需要在分类模型中进行在线适应的任务。 LMN组织以类为主键的内存。内存作为第二个提升阶段，遵循规则的神经网络，从而允许内存和主要网络起辅助作用。与现有的每个实例的内存写入MANN和使用基于LRU的内存替换不同，LMN只写入非零丢失的实例，并使用基于标签的内存替换。我们展示了各种任务包括文字建模和少量学习的重要准确性收益。在本文中，我们建立了他们的潜力，在线调整批处理训练的神经网络与域相关的标记数据在部署时间。我们表明，LMNs比其他为元学习设计的MANNs更好。我们还发现它们比用于适应特定领域标记数据的重新调整模型参数的现有技术更精确和更快。

##### URL
[https://arxiv.org/abs/1707.01461](https://arxiv.org/abs/1707.01461)

##### PDF
[https://arxiv.org/pdf/1707.01461](https://arxiv.org/pdf/1707.01461)

