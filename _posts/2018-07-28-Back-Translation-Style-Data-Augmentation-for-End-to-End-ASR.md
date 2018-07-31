---
layout: post
title: "Back-Translation-Style Data Augmentation for End-to-End ASR"
date: 2018-07-28 05:32:11
categories: arXiv_CL
tags: arXiv_CL Attention Speech_Recognition Recognition
author: Tomoki Hayashi, Shinji Watanabe, Yu Zhang, Tomoki Toda, Takaaki Hori, Ramon Astudillo, Kazuya Takeda
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we propose a novel data augmentation method for attention-based end-to-end automatic speech recognition (E2E-ASR), utilizing a large amount of text which is not paired with speech signals. Inspired by the back-translation technique proposed in the field of machine translation, we build a neural text-to-encoder model which predicts a sequence of hidden states extracted by a pre-trained E2E-ASR encoder from a sequence of characters. By using hidden states as a target instead of acoustic features, it is possible to achieve faster attention learning and reduce computational cost, thanks to sub-sampling in E2E-ASR encoder, also the use of the hidden states can avoid to model speaker dependencies unlike acoustic features. After training, the text-to-encoder model generates the hidden states from a large amount of unpaired text, then E2E-ASR decoder is retrained using the generated hidden states as additional training data. Experimental evaluation using LibriSpeech dataset demonstrates that our proposed method achieves improvement of ASR performance and reduces the number of unknown words without the need for paired data.

##### Abstract (translated by Google)
在本文中，我们提出了一种新的基于注意力的端到端自动语音识别（E2E-ASR）的数据增强方法，利用大量不与语音信号配对的文本。受机器翻译领域中提出的反向翻译技术的启发，我们构建了一个神经文本到编码器模型，该模型预测由预训练的E2E-ASR编码器从一系列字符中提取的一系列隐藏状态。通过使用隐藏状态作为目标而不是声学特征，由于E2E-ASR编码器中的子采样，可以实现更快的注意力学习并降低计算成本，同样使用隐藏状态可以避免模拟说话者依赖性。声学特征。在训练之后，文本到编码器模型从大量未配对文本生成隐藏状态，然后使用生成的隐藏状态作为附加训练数据重新训练E2E-ASR解码器。使用LibriSpeech数据集进行的实验评估表明，我们提出的方法可以提高ASR性能并减少未知单词的数量，而无需配对数据。

##### URL
[http://arxiv.org/abs/1807.10893](http://arxiv.org/abs/1807.10893)

##### PDF
[http://arxiv.org/pdf/1807.10893](http://arxiv.org/pdf/1807.10893)

