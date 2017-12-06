---
layout: post
title: 'Compression of Neural Machine Translation Models via Pruning'
date: 2016-06-29 20:36:23
categories: arXiv_CL
tags: arXiv_CL NMT Deep_Learning
author: Abigail See, Minh-Thang Luong, Christopher D. Manning
---

* content
{:toc}

##### Abstract
Neural Machine Translation (NMT), like many other deep learning domains, typically suffers from over-parameterization, resulting in large storage sizes. This paper examines three simple magnitude-based pruning schemes to compress NMT models, namely class-blind, class-uniform, and class-distribution, which differ in terms of how pruning thresholds are computed for the different classes of weights in the NMT architecture. We demonstrate the efficacy of weight pruning as a compression technique for a state-of-the-art NMT system. We show that an NMT model with over 200 million parameters can be pruned by 40% with very little performance loss as measured on the WMT'14 English-German translation task. This sheds light on the distribution of redundancy in the NMT architecture. Our main result is that with retraining, we can recover and even surpass the original performance with an 80%-pruned model.

##### Abstract (translated by Google)
神经机器翻译（NMT）和许多其他深度学习领域一样，通常会受到过度参数化的影响，导致大的存储容量。本文考察了三种简单的基于幅度的修剪方案来压缩NMT模型，即类盲，类一致和类分布，它们在NMT体系结构中对于不同类别的权重如何计算修剪阈值方面有所不同。我们证明作为最先进的NMT系统的压缩技术的减肥功效。我们表明，具有超过2亿参数的NMT模型可以被削减40％，而在WMT'14英德翻译任务上测量的性能损失很小。这揭示了NMT架构中的冗余分布。我们的主要结果是，通过再培训，我们可以恢复，甚至超过原来的表现，80％的模型。

##### URL
[https://arxiv.org/abs/1606.09274](https://arxiv.org/abs/1606.09274)

