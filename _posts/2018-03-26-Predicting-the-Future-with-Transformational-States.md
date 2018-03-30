---
layout: post
title: "Predicting the Future with Transformational States"
date: 2018-03-26 18:00:07
categories: arXiv_AI
tags: arXiv_AI Adversarial CNN RNN Prediction Quantitative
author: Andrew Jaegle, Oleh Rybkin, Konstantinos G. Derpanis, Kostas Daniilidis
mathjax: true
---

* content
{:toc}

##### Abstract
An intelligent observer looks at the world and sees not only what is, but what is moving and what can be moved. In other words, the observer sees how the present state of the world can transform in the future. We propose a model that predicts future images by learning to represent the present state and its transformation given only a sequence of images. To do so, we introduce an architecture with a latent state composed of two components designed to capture (i) the present image state and (ii) the transformation between present and future states, respectively. We couple this latent state with a recurrent neural network (RNN) core that predicts future frames by transforming past states into future states by applying the accumulated state transformation with a learned operator. We describe how this model can be integrated into an encoder-decoder convolutional neural network (CNN) architecture that uses weighted residual connections to integrate representations of the past with representations of the future. Qualitatively, our approach generates image sequences that are stable and capture realistic motion over multiple predicted frames, without requiring adversarial training. Quantitatively, our method achieves prediction results comparable to state-of-the-art results on standard image prediction benchmarks (Moving MNIST, KTH, and UCF101).

##### Abstract (translated by Google)
一位聪明的观察者看着这个世界，不仅看到了什么，而且看到了什么在移动，什么可以移动。换句话说，观察者看到了未来世界的现状如何变化。我们提出了一种模型，通过学习表示当前状态及其变换只给出一系列图像来预测未来图像。为此，我们引入了一个潜在状态的体系结构，该体系由两个组件组成，分别用于捕获（i）当前图像状态和（ii）当前状态和未来状态之间的转换。我们将这种潜在状态与循环神经网络（RNN）相结合，该核心通过将学习运算符应用累积状态转换，将过去的状态转换成未来状态，从而预测未来的帧。我们描述了如何将这个模型集成到编码器 - 解码器卷积神经网络（CNN）架构中，该架构使用加权剩余连接来整合过去的表示和未来的表示。定性地，我们的方法生成稳定的图像序列，并捕捉多个预测帧的逼真运动，而不需要对抗训练。在数量上，我们的方法实现的预测结果与标准图像预测基准（Moving MNIST，KTH和UCF101）中的最新结果相当。

##### URL
[https://arxiv.org/abs/1803.09760](https://arxiv.org/abs/1803.09760)

##### PDF
[https://arxiv.org/pdf/1803.09760](https://arxiv.org/pdf/1803.09760)

