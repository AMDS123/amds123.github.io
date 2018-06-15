---
layout: post
title: "PCAS: Pruning Channels with Attention Statistics"
date: 2018-06-14 06:28:59
categories: arXiv_CV
tags: arXiv_CV Attention Relation
author: Kohei Yamamoto, Kurato Maeno
mathjax: true
---

* content
{:toc}

##### Abstract
To implement deep neural networks on small embedded devices, conventional techniques use channel pruning looking considering manual compression rate per layer to reduce parameters. Besides it is difficult to consider the relationships between layers and it takes a lot of time for deeper models. For addressing these issues, we propose a new channel pruning technique based on attention that can evaluate the importance of channels. We improved the method with the criterion to allow the automatic channel selection using a single compression rate for the entire model. Experimental results showed that a parameter reduction of 90.8% and FLOPs reduction of 79.4% was achieved with an accuracy degradation of around 1% for the compressed ResNet-50 model on the CIFAR-10 benchmark.

##### Abstract (translated by Google)
为了在小型嵌入式设备上实现深度神经网络，传统技术使用频道修剪，考虑考虑每层的手动压缩率来减少参数。此外，很难考虑层之间的关系，深层模型需要很长时间。为了解决这些问题，我们提出了一种基于注意力的新渠道修剪技术，可以评估渠道的重要性。我们使用标准对方法进行了改进，以允许使用整个模型的单个压缩率进行自动信道选择。实验结果表明，在CIFAR-10基准测试中，压缩的ResNet-50模型的参数下降了90.8％，FLOP下降了79.4％，精度下降了1％左右。

##### URL
[http://arxiv.org/abs/1806.05382](http://arxiv.org/abs/1806.05382)

##### PDF
[http://arxiv.org/pdf/1806.05382](http://arxiv.org/pdf/1806.05382)

