---
layout: post
title: "A Wavenet for Speech Denoising"
date: 2018-01-31 09:38:44
categories: arXiv_SD
tags: arXiv_SD Inference
author: Dario Rethage, Jordi Pons, Xavier Serra
mathjax: true
---

* content
{:toc}

##### Abstract
Currently, most speech processing techniques use magnitude spectrograms as front-end and are therefore by default discarding part of the signal: the phase. In order to overcome this limitation, we propose an end-to-end learning method for speech denoising based on Wavenet. The proposed model adaptation retains Wavenet's powerful acoustic modeling capabilities, while significantly reducing its time-complexity by eliminating its autoregressive nature. Specifically, the model makes use of non-causal, dilated convolutions and predicts target fields instead of a single target sample. The discriminative adaptation of the model we propose, learns in a supervised fashion via minimizing a regression loss. These modifications make the model highly parallelizable during both training and inference. Both computational and perceptual evaluations indicate that the proposed method is preferred to Wiener filtering, a common method based on processing the magnitude spectrogram.

##### Abstract (translated by Google)
目前，大多数语音处理技术使用幅度谱图作为前端，因此默认丢弃部分信号：相位。为了克服这个局限，我们提出了一种基于Wavenet的语音去噪端到端学习方法。所提出的模型适应保留了Wavenet强大的声学建模功能，同时通过消除其自回归性质显着降低了其时间复杂性。具体来说，该模型利用非因果扩张卷积和预测目标领域，而不是一个单一的目标样本。我们提出的模型的区别性适应，通过最小化回归损失，以监督的方式学习。这些修改使得模型在训练和推理期间高度可并行化。计算和感知评估都表明，所提出的方法优于维纳滤波，这是一种基于处理幅度谱图的常用方法。

##### URL
[http://arxiv.org/abs/1706.07162](http://arxiv.org/abs/1706.07162)

##### PDF
[http://arxiv.org/pdf/1706.07162](http://arxiv.org/pdf/1706.07162)

