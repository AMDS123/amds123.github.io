---
layout: post
title: "Efficient parametrization of multi-domain deep neural networks"
date: 2018-03-27 13:55:56
categories: arXiv_CV
tags: arXiv_CV Transfer_Learning
author: Sylvestre-Alvise Rebuffi, Hakan Bilen, Andrea Vedaldi
mathjax: true
---

* content
{:toc}

##### Abstract
A practical limitation of deep neural networks is their high degree of specialization to a single task and visual domain. Recently, inspired by the successes of transfer learning, several authors have proposed to learn instead universal, fixed feature extractors that, used as the first stage of any deep network, work well for several tasks and domains simultaneously. Nevertheless, such universal features are still somewhat inferior to specialized networks. To overcome this limitation, in this paper we propose to consider instead universal parametric families of neural networks, which still contain specialized problem-specific models, but differing only by a small number of parameters. We study different designs for such parametrizations, including series and parallel residual adapters, joint adapter compression, and parameter allocations, and empirically identify the ones that yield the highest compression. We show that, in order to maximize performance, it is necessary to adapt both shallow and deep layers of a deep network, but the required changes are very small. We also show that these universal parametrization are very effective for transfer learning, where they outperform traditional fine-tuning techniques.

##### Abstract (translated by Google)
深度神经网络的一个实际限制是它们对单个任务和视觉领域的高度专业化。最近，受到转移学习的成功启发，一些作者提出要学习，而不是通用的固定特征提取器，它被用作任何深度网络的第一阶段，同时适用于多个任务和领域。尽管如此，这种普遍特征仍然比专业网络差一些。为了克服这个限制，在本文中，我们建议考虑使用神经网络的通用参数族，它仍然包含特定的特定问题模型，但只有少数参数不同。我们研究了这种参数化的不同设计，包括串联和并行残余适配器，联合适配器压缩和参数分配，并凭经验确定产生最高压缩的参数。我们表明，为了最大化性能，有必要适应深层网络的浅层和深层，但所需的更改非常小。我们还表明，这些通用参数化对于转移学习非常有效，它们超越了传统的微调技术。

##### URL
[https://arxiv.org/abs/1803.10082](https://arxiv.org/abs/1803.10082)

##### PDF
[https://arxiv.org/pdf/1803.10082](https://arxiv.org/pdf/1803.10082)

