---
layout: post
title: "End-to-End Speech Recognition From the Raw Waveform"
date: 2018-06-19 08:32:49
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition CNN Recognition
author: Neil Zeghidour, Nicolas Usunier, Gabriel Synnaeve, Ronan Collobert, Emmanuel Dupoux
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art speech recognition systems rely on fixed, hand-crafted features such as mel-filterbanks to preprocess the waveform before the training pipeline. In this paper, we study end-to-end systems trained directly from the raw waveform, building on two alternatives for trainable replacements of mel-filterbanks that use a convolutional architecture. The first one is inspired by gammatone filterbanks (Hoshen et al., 2015; Sainath et al, 2015), and the second one by the scattering transform (Zeghidour et al., 2017). We propose two modifications to these architectures and systematically compare them to mel-filterbanks, on the Wall Street Journal dataset. The first modification is the addition of an instance normalization layer, which greatly improves on the gammatone-based trainable filterbanks and speeds up the training of the scattering-based filterbanks. The second one relates to the low-pass filter used in these approaches. These modifications consistently improve performances for both approaches, and remove the need for a careful initialization in scattering-based trainable filterbanks. In particular, we show a consistent improvement in word error rate of the trainable filterbanks relatively to comparable mel-filterbanks. It is the first time end-to-end models trained from the raw signal significantly outperform mel-filterbanks on a large vocabulary task under clean recording conditions.

##### Abstract (translated by Google)
最先进的语音识别系统依靠固定的手工特征，如mel-filterbanks在训练管道之前预处理波形。在本文中，我们研究直接从原始波形训练的端到端系统，建立在两个替代方案的基础上，以便利用卷积体系结构对mel-filterbanks进行可训练替换。第一个来自gammatone滤波器（Hoshen等，2015; Sainath等，2015），第二个是散射变换（Zeghidour等，2017）。我们对这些体系结构提出两项修改，并系统地将它们与“华尔街日报”数据集中的梅尔过滤库进行比较。第一种修改是增加了一个实例标准化层，它极大地改进了基于gammatone的可训练滤波器组，并加速了基于散射滤波器组的训练。第二个涉及这些方法中使用的低通滤波器。这些修改不断提高两种方法的性能，并且不需要在基于散射的可训练滤波器组中仔细初始化。特别是，我们展示了可比较的梅尔滤波器组相对于可训练滤波器组的字错误率的一致改进。这是首次使用原始信号进行训练的端到端模型在干净记录条件下的大量词汇表上显着优于mel-filterbanks。

##### URL
[http://arxiv.org/abs/1806.07098](http://arxiv.org/abs/1806.07098)

##### PDF
[http://arxiv.org/pdf/1806.07098](http://arxiv.org/pdf/1806.07098)

