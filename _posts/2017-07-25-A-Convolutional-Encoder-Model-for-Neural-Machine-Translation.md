---
layout: post
title: "A Convolutional Encoder Model for Neural Machine Translation"
date: 2017-07-25 01:36:14
categories: arXiv_CL
tags: arXiv_CL CNN RNN
author: Jonas Gehring, Michael Auli, David Grangier, Yann N. Dauphin
mathjax: true
---

* content
{:toc}

##### Abstract
The prevalent approach to neural machine translation relies on bi-directional LSTMs to encode the source sentence. In this paper we present a faster and simpler architecture based on a succession of convolutional layers. This allows to encode the entire source sentence simultaneously compared to recurrent networks for which computation is constrained by temporal dependencies. On WMT'16 English-Romanian translation we achieve competitive accuracy to the state-of-the-art and we outperform several recently published results on the WMT'15 English-German task. Our models obtain almost the same accuracy as a very deep LSTM setup on WMT'14 English-French translation. Our convolutional encoder speeds up CPU decoding by more than two times at the same or higher accuracy as a strong bi-directional LSTM baseline.

##### Abstract (translated by Google)
神经机器翻译的流行方法依赖于双向LSTM来对源语句进行编码。在本文中，我们提出了一个更快，更简单的基于一系列卷积层的体系结构。与计算受时间依赖性约束的循环网络相比，这允许同时对整个源语句进行编码。关于WMT'16英语 - 罗马尼亚语翻译，我们实现了最先进的竞争准确性，并且胜过了最近公布的有关WMT'15英语 - 德语任务的几个结果。我们的模型在WMT'14英文 - 法文翻译中获得与深度LSTM设置几乎相同的准确度。我们的卷积编码器以相同或更高的准确度将CPU解码速度提高了两倍以上，成为强大的双向LSTM基线。

##### URL
[https://arxiv.org/abs/1611.02344](https://arxiv.org/abs/1611.02344)

##### PDF
[https://arxiv.org/pdf/1611.02344](https://arxiv.org/pdf/1611.02344)

