---
layout: post
title: "Speeding Up Neural Networks for Large Scale Classification using WTA Hashing"
date: 2015-04-28 14:17:24
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Amir H. Bakhtiary (1), Agata Lapedriza (1), David Masip (1) ((1) Universitat Oberta de Catalunya)
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we propose to use the Winner Takes All hashing technique to speed up forward propagation and backward propagation in fully connected layers in convolutional neural networks. The proposed technique reduces significantly the computational complexity, which in turn, allows us to train layers with a large number of kernels with out the associated time penalty. As a consequence we are able to train convolutional neural network on a very large number of output classes with only a small increase in the computational cost. To show the effectiveness of the technique we train a new output layer on a pretrained network using both the regular multiplicative approach and our proposed hashing methodology. Our results showed no drop in performance and demonstrate, with our implementation, a 7 fold speed up during the training.

##### Abstract (translated by Google)
在本文中，我们建议使用Winner Takes All哈希技术来加速卷积神经网络中完全连通层的前向传播和后向传播。所提出的技术大大降低了计算复杂度，这反过来又使我们能够训练具有大量内核的图层而没有相关的时间损失。因此，我们能够在很大数量的输出类别上训练卷积神经网络，而计算成本只有很小的增加。为了显示技术的有效性，我们使用规则乘法和我们提出的哈希方法在预训练网络上训练新的输出层。我们的研究结果表明，没有下降的表现，并证明，与我们的实施，在培训期间加快7倍。

##### URL
[https://arxiv.org/abs/1504.07488](https://arxiv.org/abs/1504.07488)

##### PDF
[https://arxiv.org/pdf/1504.07488](https://arxiv.org/pdf/1504.07488)

