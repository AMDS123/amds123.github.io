---
layout: post
title: "SAR Target Recognition Using the Multi-aspect-aware Bidirectional LSTM Recurrent Neural Networks"
date: 2017-07-25 04:01:25
categories: arXiv_CV
tags: arXiv_CV RNN Classification Deep_Learning Recognition
author: Fan Zhang, Chen Hu, Qiang Yin, Wei Li, Hengchao Li, Wen Hong
mathjax: true
---

* content
{:toc}

##### Abstract
The outstanding pattern recognition performance of deep learning brings new vitality to the synthetic aperture radar (SAR) automatic target recognition (ATR). However, there is a limitation in current deep learning based ATR solution that each learning process only handle one SAR image, namely learning the static scattering information, while missing the space-varying information. It is obvious that multi-aspect joint recognition introduced space-varying scattering information should improve the classification accuracy and robustness. In this paper, a novel multi-aspect-aware method is proposed to achieve this idea through the bidirectional Long Short-Term Memory (LSTM) recurrent neural networks based space-varying scattering information learning. Specifically, we first select different aspect images to generate the multi-aspect space-varying image sequences. Then, the Gabor filter and three-patch local binary pattern (TPLBP) are progressively implemented to extract a comprehensive spatial features, followed by dimensionality reduction with the Multi-layer Perceptron (MLP) network. Finally, we design a bidirectional LSTM recurrent neural network to learn the multi-aspect features with further integrating the softmax classifier to achieve target recognition. Experimental results demonstrate that the proposed method can achieve 99.9% accuracy for 10-class recognition. Besides, its anti-noise and anti-confusion performance are also better than the conventional deep learning based methods.

##### Abstract (translated by Google)
深度学习的突出模式识别性能为合成孔径雷达（SAR）自动目标识别（ATR）带来了新的活力。然而，目前基于深度学习的ATR方案存在着局限性，即每个学习过程只处理一个SAR图像，即学习静态散射信息，而忽略空间变化信息。很明显，多方位联合识别引入的空间散射信息可以提高分类精度和鲁棒性。本文提出了一种基于双向长时程记忆（LSTM）递归神经网络的空间变化散射信息学习方法，实现了该方法。具体来说，我们首先选择不同的方面图像来生成多方面的空间变化的图像序列。然后，逐步实现Gabor滤波器和三斑点局部二值模式（TPLBP）来提取综合空间特征，然后用多层感知器（MLP）网络进行降维。最后，我们设计了一个双向LSTM递归神经网络，通过进一步整合softmax分类器来实现目标识别，从而学习多方面的特征。实验结果表明，所提出的方法可以达到10级识别的99.9％的准确性。此外，其抗噪声和反混淆性能也优于传统的基于深度学习的方法。

##### URL
[https://arxiv.org/abs/1707.09875](https://arxiv.org/abs/1707.09875)

##### PDF
[https://arxiv.org/pdf/1707.09875](https://arxiv.org/pdf/1707.09875)

