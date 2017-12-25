---
layout: post
title: "On Using Backpropagation for Speech Texture Generation and Voice Conversion"
date: 2017-12-22 09:19:23
categories: arXiv_SD
tags: arXiv_SD Speech_Recognition Style_Transfer CNN Recognition
author: Jan Chorowski, Ron J. Weiss, Rif A. Saurous, Samy Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
Inspired by recent work on neural network image generation which rely on backpropagation towards the network inputs, we present a proof-of-concept system for speech texture synthesis and voice conversion based on two mechanisms: approximate inversion of the representation learned by a speech recognition neural network, and on matching statistics of neuron activations between different source and target utterances. Similar to image texture synthesis and neural style transfer, the system works by optimizing a cost function with respect to the input waveform samples. To this end we use a differentiable mel-filterbank feature extraction pipeline and train a convolutional CTC speech recognition network. Our system is able to extract speaker characteristics from very limited amounts of target speaker data, as little as a few seconds, and can be used to generate realistic speech babble or reconstruct an utterance in a different voice.

##### Abstract (translated by Google)
受近期有关网络输入反向传播的神经网络图像生成工作的启发，我们提出了基于两种机制的语音纹理合成和语音转换的概念验证系统：由语音识别神经学习的表示的近似反演网络，以及不同来源和目标话语之间神经元激活的匹配统计。与图像纹理合成和神经风格转换类似，系统通过针对输入波形样本优化成本函数来工作。为此，我们使用可微分的mel-filterbank特征提取流水线并训练一​​个卷积CTC语音识别网络。我们的系统能够从数量非常有限的目标说话人数据中提取说话人特征，仅需几秒钟，就可以用来生成逼真的语音唠叨或用不同的语音重建话语。

##### URL
[https://arxiv.org/abs/1712.08363](https://arxiv.org/abs/1712.08363)

##### PDF
[https://arxiv.org/pdf/1712.08363](https://arxiv.org/pdf/1712.08363)

