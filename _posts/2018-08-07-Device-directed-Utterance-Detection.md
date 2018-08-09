---
layout: post
title: "Device-directed Utterance Detection"
date: 2018-08-07 18:19:30
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Embedding RNN Detection Recognition
author: Sri Harish Mallidi, Roland Maas, Kyle Goehner, Ariya Rastrow, Spyros Matsoukas, Bj&#xf6;rn Hoffmeister
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we propose a classifier for distinguishing device-directed queries from background speech in the context of interactions with voice assistants. Applications include rejection of false wake-ups or unintended interactions as well as enabling wake-word free follow-up queries. Consider the example interaction: $"Computer,~play~music", "Computer,~reduce~the~volume"$. In this interaction, the user needs to repeat the wake-word ($Computer$) for the second query. To allow for more natural interactions, the device could immediately re-enter listening state after the first query (without wake-word repetition) and accept or reject a potential follow-up as device-directed or background speech. The proposed model consists of two long short-term memory (LSTM) neural networks trained on acoustic features and automatic speech recognition (ASR) 1-best hypotheses, respectively. A feed-forward deep neural network (DNN) is then trained to combine the acoustic and 1-best embeddings, derived from the LSTMs, with features from the ASR decoder. Experimental results show that ASR decoder, acoustic embeddings, and 1-best embeddings yield an equal-error-rate (EER) of $9.3~\%$, $10.9~\%$ and $20.1~\%$, respectively. Combination of the features resulted in a $44~\%$ relative improvement and a final EER of $5.2~\%$.

##### Abstract (translated by Google)
在这项工作中，我们提出了一种分类器，用于在与语音助理的交互环境中区分设备导向查询和背景语音。应用程序包括拒绝错误唤醒或非预期的交互以及启用无唤醒字的后续查询。考虑示例交互：$“计算机，〜播放〜音乐”，“计算机，〜减少〜音量”$。在此交互中，用户需要为第二个查询重复唤醒字（$ Computer $）。为了允许更自然的交互，设备可以在第一次查询之后立即重新进入收听状态（没有唤醒字重复）并且接受或拒绝作为设备指导或背景语音的潜在跟进。所提出的模型包括分别在声学特征和自动语音识别（ASR）1最佳假设上训练的两个长短期记忆（LSTM）神经网络。然后训练前馈深度神经网络（DNN）以将来自LSTM的声学和1最佳嵌入与来自ASR解码器的特征组合。实验结果表明，ASR解码器，声学嵌入和1-best嵌入分别产生$ 9.3~ \％$，$ 10.9~ \％$和$ 20.1~ \％$的等误差率（EER）。这些功能的组合导致$ 44~ \％$的相对改善，最终的EER为$ 5.2~ \％$。

##### URL
[http://arxiv.org/abs/1808.02504](http://arxiv.org/abs/1808.02504)

##### PDF
[http://arxiv.org/pdf/1808.02504](http://arxiv.org/pdf/1808.02504)

