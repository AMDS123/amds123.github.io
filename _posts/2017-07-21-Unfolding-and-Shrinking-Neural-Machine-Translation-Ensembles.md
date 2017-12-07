---
layout: post
title: "Unfolding and Shrinking Neural Machine Translation Ensembles"
date: 2017-07-21 13:04:22
categories: arXiv_CL
tags: arXiv_CL NMT Prediction
author: Felix Stahlberg, Bill Byrne
mathjax: true
---

* content
{:toc}

##### Abstract
Ensembling is a well-known technique in neural machine translation (NMT) to improve system performance. Instead of a single neural net, multiple neural nets with the same topology are trained separately, and the decoder generates predictions by averaging over the individual models. Ensembling often improves the quality of the generated translations drastically. However, it is not suitable for production systems because it is cumbersome and slow. This work aims to reduce the runtime to be on par with a single system without compromising the translation quality. First, we show that the ensemble can be unfolded into a single large neural network which imitates the output of the ensemble system. We show that unfolding can already improve the runtime in practice since more work can be done on the GPU. We proceed by describing a set of techniques to shrink the unfolded network by reducing the dimensionality of layers. On Japanese-English we report that the resulting network has the size and decoding speed of a single NMT network but performs on the level of a 3-ensemble system.

##### Abstract (translated by Google)
在神经机器翻译（NMT）中，合成是一种众所周知的技术，以提高系统性能。代替单个神经网络，具有相同拓扑的多个神经网络被单独训练，并且解码器通过对各个模型进行平均来生成预测。拼版通常会大大提高生成的翻译质量。但是，由于繁琐和缓慢，不适用于生产系统。这项工作旨在减少运行时间与单个系统相当，而不会影响翻译质量。首先，我们证明集合可以展开成一个模拟合奏系统输出的单个大型神经网络。我们证明展开已经可以在实践中提高运行时间，因为可以在GPU上完成更多的工作。我们继续描述一套缩小展开网络的技术，通过减少图层的维度。在日文 - 英文中，我们报告了由此产生的网络具有单个NMT网络的大小和解码速度，但是在三系统级别上执行。

##### URL
[https://arxiv.org/abs/1704.03279](https://arxiv.org/abs/1704.03279)

##### PDF
[https://arxiv.org/pdf/1704.03279](https://arxiv.org/pdf/1704.03279)

