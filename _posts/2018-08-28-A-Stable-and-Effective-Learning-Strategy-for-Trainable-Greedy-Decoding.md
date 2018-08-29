---
layout: post
title: "A Stable and Effective Learning Strategy for Trainable Greedy Decoding"
date: 2018-08-28 03:35:54
categories: arXiv_CL
tags: arXiv_CL Reinforcement_Learning
author: Yun Chen, Victor O.K. Li, Kyunghyun Cho, Samuel R. Bowman
mathjax: true
---

* content
{:toc}

##### Abstract
Beam search is a widely used approximate search strategy for neural network decoders, and it generally outperforms simple greedy decoding on tasks like machine translation. However, this improvement comes at substantial computational cost. In this paper, we propose a flexible new method that allows us to reap nearly the full benefits of beam search with nearly no additional computational cost. The method revolves around a small neural network actor that is trained to observe and manipulate the hidden state of a previously-trained decoder. To train this actor network, we introduce the use of a pseudo-parallel corpus built using the output of beam search on a base model, ranked by a target quality metric like BLEU. Our method is inspired by earlier work on this problem, but requires no reinforcement learning, and can be trained reliably on a range of models. Experiments on three parallel corpora and three architectures show that the method yields substantial improvements in translation quality and speed over each base system.

##### Abstract (translated by Google)
波束搜索是神经网络解码器中广泛使用的近似搜索策略，它通常优于机器翻译等任务的简单贪婪解码。然而，这种改进带来了大量的计算成本。在本文中，我们提出了一种灵活的新方法，它使我们几乎可以获得光束搜索的全部好处，几乎不需要额外的计算成本。该方法围绕一个小型神经网络演员，该演员被训练以观察和操纵先前训练的解码器的隐藏状态。为了训练这个演员网络，我们介绍了在基础模型上使用波束搜索输出构建的伪平行语料库的使用，按照像BLEU这样的目标质量度量进行排序。我们的方法受到早期关于这个问题的工作的启发，但不需要强化学习，并且可以在一系列模型上可靠地训练。在三个平行语料库和三个体系结构上的实验表明，该方法在每个基本系统上产生翻译质量和速度的显着改进。

##### URL
[http://arxiv.org/abs/1804.07915](http://arxiv.org/abs/1804.07915)

##### PDF
[http://arxiv.org/pdf/1804.07915](http://arxiv.org/pdf/1804.07915)

