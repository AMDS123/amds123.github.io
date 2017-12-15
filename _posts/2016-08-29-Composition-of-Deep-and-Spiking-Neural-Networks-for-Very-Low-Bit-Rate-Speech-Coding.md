---
layout: post
title: "Composition of Deep and Spiking Neural Networks for Very Low Bit Rate Speech Coding"
date: 2016-08-29 07:56:01
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Detection Recognition
author: Milos Cernak, Alexandros Lazaridis, Afsaneh Asaei, Philip N. Garner
mathjax: true
---

* content
{:toc}

##### Abstract
Most current very low bit rate (VLBR) speech coding systems use hidden Markov model (HMM) based speech recognition/synthesis techniques. This allows transmission of information (such as phonemes) segment by segment that decreases the bit rate. However, the encoder based on a phoneme speech recognition may create bursts of segmental errors. Segmental errors are further propagated to optional suprasegmental (such as syllable) information coding. Together with the errors of voicing detection in pitch parametrization, HMM-based speech coding creates speech discontinuities and unnatural speech sound artefacts. In this paper, we propose a novel VLBR speech coding framework based on neural networks (NNs) for end-to-end speech analysis and synthesis without HMMs. The speech coding framework relies on phonological (sub-phonetic) representation of speech, and it is designed as a composition of deep and spiking NNs: a bank of phonological analysers at the transmitter, and a phonological synthesizer at the receiver, both realised as deep NNs, and a spiking NN as an incremental and robust encoder of syllable boundaries for coding of continuous fundamental frequency (F0). A combination of phonological features defines much more sound patterns than phonetic features defined by HMM-based speech coders, and the finer analysis/synthesis code contributes into smoother encoded speech. Listeners significantly prefer the NN-based approach due to fewer discontinuities and speech artefacts of the encoded speech. A single forward pass is required during the speech encoding and decoding. The proposed VLBR speech coding operates at a bit rate of approximately 360 bits/s.

##### Abstract (translated by Google)
大多数当前非常低比特率（VLBR）语音编码系统使用基于隐马尔可夫模型（HMM）的语音识别/合成技术。这允许逐段传输信息（例如音素），从而降低比特率。然而，基于音素语音识别的编码器可能会产生分段错误的突发。分段错误进一步传播到可选的超分段（例如音节）信息编码。再加上音调参数化中浊音检测的误差，基于HMM的语音编码会产生语音不连续性和不自然的语音伪像。在本文中，我们提出了一种基于神经网络（NN）的新颖的VLBR语音编码框架，用于无HMM的端到端语音分析和合成。语音编码框架依赖于语音的语音（子语音）表示，它被设计成一个深层神经网络的组成部分：在发射机上的一组语音分析器和在接收机上的一个语音合成器，神经网络和作为连续基频（F0）编码的音节边界的增量和鲁棒编码器的尖峰神经网络。语音特征的组合定义比由基于HMM的语音编码器定义的语音特征更多的声音模式，更精细的分析/综合代码贡献为更平滑的编码语音。由于较少的不连续性和编码语音的语音伪像，听众显着偏爱基于NN的方法。在语音编码和解码期间需要单个正向通道。所提出的VLBR语音编码以大约360比特/秒的比特率进行操作。

##### URL
[https://arxiv.org/abs/1604.04383](https://arxiv.org/abs/1604.04383)

##### PDF
[https://arxiv.org/pdf/1604.04383](https://arxiv.org/pdf/1604.04383)

