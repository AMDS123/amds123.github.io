---
layout: post
title: 'State-of-the-art Speech Recognition With Sequence-to-Sequence Models'
date: 2017-12-06 09:57:20
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition RNN Recognition
author: Chung-Cheng Chiu, Tara N. Sainath, Yonghui Wu, Rohit Prabhavalkar, Patrick Nguyen, Zhifeng Chen, Anjuli Kannan, Ron J. Weiss, Kanishka Rao, Katya Gonina, Navdeep Jaitly, Bo Li, Jan Chorowski, Michiel Bacchiani
---

* content
{:toc}

##### Abstract
Attention-based encoder-decoder architectures such as Listen, Attend, and Spell (LAS), subsume the acoustic, pronunciation and language model components of a traditional automatic speech recognition (ASR) system into a single neural network. In our previous work, we have shown that such architectures are comparable to state-of-the-art ASR systems on dictation tasks, but it was not clear if such architectures would be practical for more challenging tasks such as voice search. In this work, we explore a variety of structural and optimization improvements to our LAS model which significantly improve performance. On the structural side, we show that word piece models can be used instead of graphemes. We introduce a novel multi-head attention architecture, which offers improvements over the commonly-used single-head attention. On the optimization side, we explore techniques such as synchronous training, scheduled sampling, label smoothing, and applying minimum word error rate optimization, which are all shown to improve accuracy. We present results with a unidirectional LSTM encoder for streaming recognition. On a 12,500~hour voice search task, we find that the proposed changes improve the WER of the LAS system from 9.2% to 5.8%, which corresponds to a 13% relative improvement over the best conventional system which achieves 6.7% WER.

##### Abstract (translated by Google)
传统的自动语音识别（ASR）系统的声学，发音和语言模型组件包括基于注意力的编码器 - 解码器架构，例如Listen，Attend和Spell（LAS），将其组合成单个神经网络。在我们以前的工作中，我们已经表明，这样的架构在听写任务方面与先进的ASR系统相当，但是这样的架构对于诸如语音搜索等更具挑战性的任务是否可行是不明确的。在这项工作中，我们探索了LAS模型的各种结构和优化改进，从而显着提高了性能。在结构方面，我们表明，单词模型可以用来代替字形。我们引入了一种新颖的多头注意架构，它比常用的单头注意力提供了改进。在优化方面，我们探索了同步训练，调度采样，标签平滑，以及应用最小误码率优化等技术，这些都是为了提高精度。我们用一个单向LSTM编码器来呈现流式识别结果。在12,500小时的语音搜索任务中，我们发现所提出的变化将LAS系统的WER从9.2％提高到5.8％，这相对于最佳传统系统（相对于最佳传统系统达到6.7％WER）提高了13％。

##### URL
[http://arxiv.org/abs/1712.01769](http://arxiv.org/abs/1712.01769)

