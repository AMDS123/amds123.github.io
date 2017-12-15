---
layout: post
title: "A Neural Transducer"
date: 2016-08-04 23:31:46
categories: arXiv_CL
tags: arXiv_CL Attention Prediction
author: Navdeep Jaitly, David Sussillo, Quoc V. Le, Oriol Vinyals, Ilya Sutskever, Samy Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
Sequence-to-sequence models have achieved impressive results on various tasks. However, they are unsuitable for tasks that require incremental predictions to be made as more data arrives or tasks that have long input sequences and output sequences. This is because they generate an output sequence conditioned on an entire input sequence. In this paper, we present a Neural Transducer that can make incremental predictions as more input arrives, without redoing the entire computation. Unlike sequence-to-sequence models, the Neural Transducer computes the next-step distribution conditioned on the partially observed input sequence and the partially generated sequence. At each time step, the transducer can decide to emit zero to many output symbols. The data can be processed using an encoder and presented as input to the transducer. The discrete decision to emit a symbol at every time step makes it difficult to learn with conventional backpropagation. It is however possible to train the transducer by using a dynamic programming algorithm to generate target discrete decisions. Our experiments show that the Neural Transducer works well in settings where it is required to produce output predictions as data come in. We also find that the Neural Transducer performs well for long sequences even when attention mechanisms are not used.

##### Abstract (translated by Google)
序列 - 序列模型在各种任务中取得了令人印象深刻的结果。然而，它们不适合于需要随着更多数据到达或者具有长输入序列和输出序列的任务而进行增量预测的任务。这是因为它们会产生一个输出序列，以整个输入序列为条件。在本文中，我们提出一个神经传感器，可以进行增量预测，因为更多的输入到达，而无需重新整个计算。与序列到序列模型不同的是，神经传感器计算下一步分布，条件是部分观察到的输入序列和部分产生的序列。在每个时间步，传感器可以决定发出零到许多输出符号。数据可以使用一个编码器进行处理，并作为传感器的输入。在每个时间步发出一个符号的离散决定使得用传统反向传播难以学习。然而，可以通过使用动态编程算法来训练换能器以生成目标离散决策。我们的实验表明，神经传感器在数据进入时需要产生输出预测的环境中工作良好。我们还发现，即使在不使用关注机制的情况下，神经传感器也能很好地处理长序列。

##### URL
[https://arxiv.org/abs/1511.04868](https://arxiv.org/abs/1511.04868)

##### PDF
[https://arxiv.org/pdf/1511.04868](https://arxiv.org/pdf/1511.04868)

