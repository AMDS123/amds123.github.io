---
layout: post
title: "Modeling Sparse Deviations for Compressed Sensing using Generative Models"
date: 2018-07-04 03:57:21
categories: arXiv_AI
tags: arXiv_AI Sparse
author: Manik Dhar, Aditya Grover, Stefano Ermon
mathjax: true
---

* content
{:toc}

##### Abstract
In compressed sensing, a small number of linear measurements can be used to reconstruct an unknown signal. Existing approaches leverage assumptions on the structure of these signals, such as sparsity or the availability of a generative model. A domain-specific generative model can provide a stronger prior and thus allow for recovery with far fewer measurements. However, unlike sparsity-based approaches, existing methods based on generative models guarantee exact recovery only over their support, which is typically only a small subset of the space on which the signals are defined. We propose Sparse-Gen, a framework that allows for sparse deviations from the support set, thereby achieving the best of both worlds by using a domain specific prior and allowing reconstruction over the full space of signals. Theoretically, our framework provides a new class of signals that can be acquired using compressed sensing, reducing classic sparse vector recovery to a special case and avoiding the restrictive support due to a generative model prior. Empirically, we observe consistent improvements in reconstruction accuracy over competing approaches, especially in the more practical setting of transfer compressed sensing where a generative model for a data-rich, source domain aids sensing on a data-scarce, target domain.

##### Abstract (translated by Google)
在压缩感测中，可以使用少量线性测量来重建未知信号。现有方法利用对这些信号结构的假设，例如稀疏性或生成模型的可用性。特定领域的生成模型可以提供更强的先验，因此允许以更少的测量进行恢复。然而，与基于稀疏性的方法不同，基于生成模型的现有方法仅保证在其支持下的精确恢复，其通常仅是定义信号的空间的一小部分。我们提出稀疏Gen，这是一个允许与支持集稀疏偏离的框架，从而通过使用特定于域的先验并允许在整个信号空间上进行重建来实现两个世界中的最佳。从理论上讲，我们的框架提供了一类新的信号，可以使用压缩感知获取，将经典稀疏矢量恢复减少到特殊情况，并避免由于生成模型先前的限制性支持。根据经验，我们观察到重建精度相对于竞争方法的持续改进，特别是在转移压缩感知的更实际的设置中，其中用于数据丰富的源域的生成模型有助于在数据稀缺的目标域上进行感测。

##### URL
[http://arxiv.org/abs/1807.01442](http://arxiv.org/abs/1807.01442)

##### PDF
[http://arxiv.org/pdf/1807.01442](http://arxiv.org/pdf/1807.01442)

