---
layout: post
title: "Machine Speech Chain with One-shot Speaker Adaptation"
date: 2018-03-28 11:06:15
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Deep_Learning Recognition
author: Andros Tjandra, Sakriani Sakti, Satoshi Nakamura
mathjax: true
---

* content
{:toc}

##### Abstract
In previous work, we developed a closed-loop speech chain model based on deep learning, in which the architecture enabled the automatic speech recognition (ASR) and text-to-speech synthesis (TTS) components to mutually improve their performance. This was accomplished by the two parts teaching each other using both labeled and unlabeled data. This approach could significantly improve model performance within a single-speaker speech dataset, but only a slight increase could be gained in multi-speaker tasks. Furthermore, the model is still unable to handle unseen speakers. In this paper, we present a new speech chain mechanism by integrating a speaker recognition model inside the loop. We also propose extending the capability of TTS to handle unseen speakers by implementing one-shot speaker adaptation. This enables TTS to mimic voice characteristics from one speaker to another with only a one-shot speaker sample, even from a text without any speaker information. In the speech chain loop mechanism, ASR also benefits from the ability to further learn an arbitrary speaker's characteristics from the generated speech waveform, resulting in a significant improvement in the recognition rate.

##### Abstract (translated by Google)
在以前的工作中，我们开发了一种基于深度学习的闭环语音链模型，其中该结构使自动语音识别（ASR）和文本到语音合成（TTS）组件能够相互提高其性能。这是通过两部分使用标记数据和未标记数据彼此教导完成的。这种方法可以显着提高单个说话人语音数据集中的模型性能，但是在多个说话人任务中只能稍微增加。此外，该模型仍然无法处理看不见的演讲者。在本文中，我们通过在循环内部集成说话人识别模型来提出一种新的语音链机制。我们还建议通过实施一次性演讲者适应来扩展TTS处理看不见的演讲者的能力。这使得TTS能够仅使用一次性扬声器样本模拟从一个扬声器到另一个扬声器的语音特性，即使是没有任何扬声器信息的文本。在语音链循环机制中，ASR还能够从生成的语音波形中进一步学习任意说话人特征的能力，从而显着提高识别率。

##### URL
[https://arxiv.org/abs/1803.10525](https://arxiv.org/abs/1803.10525)

##### PDF
[https://arxiv.org/pdf/1803.10525](https://arxiv.org/pdf/1803.10525)

