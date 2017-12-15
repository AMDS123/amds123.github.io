---
layout: post
title: "Outrageously Large Neural Networks: The Sparsely-Gated Mixture-of-Experts Layer"
date: 2017-01-23 18:10:00
categories: arXiv_SD
tags: arXiv_SD Sparse Knowledge CNN RNN Language_Model
author: Noam Shazeer, Azalia Mirhoseini, Krzysztof Maziarz, Andy Davis, Quoc Le, Geoffrey Hinton, Jeff Dean
mathjax: true
---

* content
{:toc}

##### Abstract
The capacity of a neural network to absorb information is limited by its number of parameters. Conditional computation, where parts of the network are active on a per-example basis, has been proposed in theory as a way of dramatically increasing model capacity without a proportional increase in computation. In practice, however, there are significant algorithmic and performance challenges. In this work, we address these challenges and finally realize the promise of conditional computation, achieving greater than 1000x improvements in model capacity with only minor losses in computational efficiency on modern GPU clusters. We introduce a Sparsely-Gated Mixture-of-Experts layer (MoE), consisting of up to thousands of feed-forward sub-networks. A trainable gating network determines a sparse combination of these experts to use for each example. We apply the MoE to the tasks of language modeling and machine translation, where model capacity is critical for absorbing the vast quantities of knowledge available in the training corpora. We present model architectures in which a MoE with up to 137 billion parameters is applied convolutionally between stacked LSTM layers. On large language modeling and machine translation benchmarks, these models achieve significantly better results than state-of-the-art at lower computational cost.

##### Abstract (translated by Google)
神经网络吸收信息的能力受其参数数量的限制。有条件的计算，其中部分网络在每个实例的基础上是活跃的，在理论上已经被提出作为在不增加计算量的情况下显着增加模型容量的一种方式。然而在实践中，存在显着的算法和性能挑战。在这项工作中，我们解决了这些挑战，并最终实现了条件计算的承诺，实现了1000倍以上的模型容量提升，而现代GPU集群的计算效率只有轻微的损失。我们引入了一个由多达数千个前馈子网组成的分散门控混合专家层（MoE）。可训练的门控网络确定了这些专家的稀疏组合，以用于每个示例。我们将教育部应用于语言建模和机器翻译的任务，其中模型能力对于吸收训练语料库中大量的知识是至关重要的。我们提出模型架构，其中具有高达1370亿参数的MoE被卷积地应用在堆叠的LSTM层之间。在大型语言建模和机器翻译基准测试中，这些模型以较低的计算成本获得比现有技术更好的结果。

##### URL
[https://arxiv.org/abs/1701.06538](https://arxiv.org/abs/1701.06538)

##### PDF
[https://arxiv.org/pdf/1701.06538](https://arxiv.org/pdf/1701.06538)

