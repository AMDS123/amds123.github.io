---
layout: post
title: "ClariNet: Parallel Wave Generation in End-to-End Text-to-Speech"
date: 2018-07-19 08:15:41
categories: arXiv_AI
tags: arXiv_AI CNN
author: Wei Ping, Kainan Peng, Jitong Chen
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we propose an alternative solution for parallel wave generation by WaveNet. In contrast to parallel WaveNet (Oord et al., 2018), we distill a Gaussian inverse autoregressive flow from the autoregressive WaveNet by minimizing a novel regularized KL divergence between their highly-peaked output distributions. Our method computes the KL divergence in closed-form, which simplifies the training algorithm and provides very efficient distillation. In addition, we propose the first text-to-wave neural architecture for speech synthesis, which is fully convolutional and enables fast end-to-end training from scratch. It significantly outperforms the previous pipeline that connects a text-to-spectrogram model to a separately trained WaveNet (Ping et al., 2017). We also successfully distill a parallel waveform synthesizer conditioned on the hidden representation in this end-to-end model.

##### Abstract (translated by Google)
在这项工作中，我们提出了WaveNet产生并行波的替代解决方案。与并行WaveNet（Oord et al。，2018）相比，我们通过最小化其高峰值输出分布之间的新的正则化KL散度，从自回归WaveNet中提取高斯逆自回归流。我们的方法以闭合形式计算KL分歧，这简化了训练算法并提供了非常有效的蒸馏。此外，我们提出了第一个用于语音合成的文本到波形神经结构，它是完全卷积的，可以从头开始快速的端到端训练。它明显优于以前将文本到频谱图模型连接到经过单独训练的WaveNet的管道（Ping等，2017）。我们还成功地提取了一个以这种端到端模型中的隐藏表示为条件的并行波形合成器。

##### URL
[http://arxiv.org/abs/1807.07281](http://arxiv.org/abs/1807.07281)

##### PDF
[http://arxiv.org/pdf/1807.07281](http://arxiv.org/pdf/1807.07281)

