---
layout: post
title: "Recurrent Models for Auditory Attention in Multi-Microphone Distance Speech Recognition"
date: 2016-01-07 22:16:54
categories: arXiv_CL
tags: arXiv_CL Knowledge Attention Speech_Recognition RNN Recognition
author: Suyoun Kim, Ian Lane
mathjax: true
---

* content
{:toc}

##### Abstract
Integration of multiple microphone data is one of the key ways to achieve robust speech recognition in noisy environments or when the speaker is located at some distance from the input device. Signal processing techniques such as beamforming are widely used to extract a speech signal of interest from background noise. These techniques, however, are highly dependent on prior spatial information about the microphones and the environment in which the system is being used. In this work, we present a neural attention network that directly combines multi-channel audio to generate phonetic states without requiring any prior knowledge of the microphone layout or any explicit signal preprocessing for speech enhancement. We embed an attention mechanism within a Recurrent Neural Network (RNN) based acoustic model to automatically tune its attention to a more reliable input source. Unlike traditional multi-channel preprocessing, our system can be optimized towards the desired output in one step. Although attention-based models have recently achieved impressive results on sequence-to-sequence learning, no attention mechanisms have previously been applied to learn potentially asynchronous and non-stationary multiple inputs. We evaluate our neural attention model on the CHiME-3 challenge task, and show that the model achieves comparable performance to beamforming using a purely data-driven method.

##### Abstract (translated by Google)
多个麦克风数据的集成是在嘈杂的环境中实现鲁棒语音识别或当扬声器位于距输入设备一定距离时的关键方式之一。诸如波束形成的信号处理技术被广泛用于从背景噪声中提取感兴趣的语音信号。然而，这些技术高度依赖于关于麦克风的先前空间信息以及系统正在使用的环境。在这项工作中，我们提出了一个神经关注网络，直接结合多声道音频生成语音状态，而不需要任何事先知道的麦克风布局或任何明确的信号预处理语音增强。我们在基于循环神经网络（RNN）的声学模型中嵌入了一个关注机制，以便将其注意力自动调整为更可靠的输入源。与传统的多通道预处理不同，我们的系统可以一步优化到所需的输出。尽管基于关注的模型最近在序列到序列学习方面取得了令人印象深刻的结果，但以前没有人应用关注机制来学习潜在的异步和非平稳多输入。我们在CHiME-3挑战任务上评估我们的神经注意模型，并且证明该模型使用纯粹的数据驱动方法达到与波束形成相当的性能。

##### URL
[https://arxiv.org/abs/1511.06407](https://arxiv.org/abs/1511.06407)

##### PDF
[https://arxiv.org/pdf/1511.06407](https://arxiv.org/pdf/1511.06407)

