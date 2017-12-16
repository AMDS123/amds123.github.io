---
layout: post
title: "Learning Accurate Low-Bit Deep Neural Networks with Stochastic Quantization"
date: 2017-08-03 05:16:25
categories: arXiv_CV
tags: arXiv_CV
author: Yinpeng Dong, Renkun Ni, Jianguo Li, Yurong Chen, Jun Zhu, Hang Su
mathjax: true
---

* content
{:toc}

##### Abstract
Low-bit deep neural networks (DNNs) become critical for embedded applications due to their low storage requirement and computing efficiency. However, they suffer much from the non-negligible accuracy drop. This paper proposes the stochastic quantization (SQ) algorithm for learning accurate low-bit DNNs. The motivation is due to the following observation. Existing training algorithms approximate the real-valued elements/filters with low-bit representation all together in each iteration. The quantization errors may be small for some elements/filters, while are remarkable for others, which lead to inappropriate gradient direction during training, and thus bring notable accuracy drop. Instead, SQ quantizes a portion of elements/filters to low-bit with a stochastic probability inversely proportional to the quantization error, while keeping the other portion unchanged with full-precision. The quantized and full-precision portions are updated with corresponding gradients separately in each iteration. The SQ ratio is gradually increased until the whole network is quantized. This procedure can greatly compensate the quantization error and thus yield better accuracy for low-bit DNNs. Experiments show that SQ can consistently and significantly improve the accuracy for different low-bit DNNs on various datasets and various network structures.

##### Abstract (translated by Google)
低位深度神经网络（DNN）由于其低存储要求和计算效率而成为嵌入式应用的关键。然而，他们受到不可忽视的精度下降的很大影响。本文提出了用于学习准确的低位DNN的随机量化（SQ）算法。动机是由于以下观察。现有的训练算法在每次迭代中一起逼近具有低比特表示的实值元素/滤波器。某些元素/滤波器的量化误差可能较小，而其他元素的量化误差较小，导致训练过程中梯度方向不适当，从而导致精度下降。取而代之，SQ将一部分元素/滤波器量化为低比特，其随机概率与量化误差成反比，而另一部分以全精度保持不变。量化和全精度部分在每次迭代中分别用相应的梯度更新。 SQ比率逐渐增加，直到整个网络被量化。这个过程可以极大地补偿量化误差，从而为低位DNN提供更好的精度。实验表明，SQ可以一致地显着提高各种数据集和各种网络结构上的不同低位DNN的精度。

##### URL
[https://arxiv.org/abs/1708.01001](https://arxiv.org/abs/1708.01001)

##### PDF
[https://arxiv.org/pdf/1708.01001](https://arxiv.org/pdf/1708.01001)

