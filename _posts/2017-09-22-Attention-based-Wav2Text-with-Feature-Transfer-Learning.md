---
layout: post
title: "Attention-based Wav2Text with Feature Transfer Learning"
date: 2017-09-22 15:38:09
categories: arXiv_CL
tags: arXiv_CL Attention Speech_Recognition Transfer_Learning Deep_Learning Recognition
author: Andros Tjandra, Sakriani Sakti, Satoshi Nakamura
mathjax: true
---

* content
{:toc}

##### Abstract
Conventional automatic speech recognition (ASR) typically performs multi-level pattern recognition tasks that map the acoustic speech waveform into a hierarchy of speech units. But, it is widely known that information loss in the earlier stage can propagate through the later stages. After the resurgence of deep learning, interest has emerged in the possibility of developing a purely end-to-end ASR system from the raw waveform to the transcription without any predefined alignments and hand-engineered models. However, the successful attempts in end-to-end architecture still used spectral-based features, while the successful attempts in using raw waveform were still based on the hybrid deep neural network - Hidden Markov model (DNN-HMM) framework. In this paper, we construct the first end-to-end attention-based encoder-decoder model to process directly from raw speech waveform to the text transcription. We called the model as "Attention-based Wav2Text". To assist the training process of the end-to-end model, we propose to utilize a feature transfer learning. Experimental results also reveal that the proposed Attention-based Wav2Text model directly with raw waveform could achieve a better result in comparison with the attentional encoder-decoder model trained on standard front-end filterbank features.

##### Abstract (translated by Google)
传统的自动语音识别（ASR）通常执行将声学语音波形映射到语音单元分层结构的多级模式识别任务。但是，众所周知，前期的信息损失可以通过后期传播。在深度学习再度兴起之后，人们开始关注从原始波形到转录的纯粹的端到端ASR系统的可能性，而没有任何预定义的对齐和手工模型。然而，端到端体系结构的成功尝试仍然使用基于频谱的特征，而使用原始波形的成功尝试仍然基于混合深度神经网络 - 隐马尔可夫模型（DNN-HMM）框架。在本文中，我们构建了第一个端到端的基于注意的编码器 - 解码器模型，从原始语音波形直接处理到文本转录。我们称这个模型为“基于注意力的Wav2Text”。为了协助端到端模型的训练过程，我们建议使用特征转移学习。实验结果还表明，与标准前端滤波器组特征训练的注意编码器 - 解码器模型相比，所提出的基于注意的Wav2Text模型直接与原始波形相比可以取得更好的效果。

##### URL
[https://arxiv.org/abs/1709.07814](https://arxiv.org/abs/1709.07814)

##### PDF
[https://arxiv.org/pdf/1709.07814](https://arxiv.org/pdf/1709.07814)

