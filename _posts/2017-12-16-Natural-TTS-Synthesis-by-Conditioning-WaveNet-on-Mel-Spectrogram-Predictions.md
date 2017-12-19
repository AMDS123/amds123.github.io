---
layout: post
title: "Natural TTS Synthesis by Conditioning WaveNet on Mel Spectrogram Predictions"
date: 2017-12-16 00:51:40
categories: arXiv_CL
tags: arXiv_CL Embedding Prediction
author: Jonathan Shen, Ruoming Pang, Ron J. Weiss, Mike Schuster, Navdeep Jaitly, Zongheng Yang, Zhifeng Chen, Yu Zhang, Yuxuan Wang, RJ Skerry-Ryan, Rif A. Saurous, Yannis Agiomyrgiannakis, Yonghui Wu
mathjax: true
---

* content
{:toc}

##### Abstract
This paper describes Tacotron 2, a neural network architecture for speech synthesis directly from text. The system is composed of a recurrent sequence-to-sequence feature prediction network that maps character embeddings to mel-scale spectrograms, followed by a modified WaveNet model acting as a vocoder to synthesize timedomain waveforms from those spectrograms. Our model achieves a mean opinion score (MOS) of 4.53 comparable to a MOS of 4.58 for professionally recorded speech. To validate our design choices, we present ablation studies of key components of our system and evaluate the impact of using mel spectrograms as the input to WaveNet instead of linguistic, duration, and F0 features. We further demonstrate that using a compact acoustic intermediate representation enables significant simplification of the WaveNet architecture.

##### Abstract (translated by Google)
本文介绍了Tacotron 2，一个直接从文本语音合成的神经网络架构。该系统由经常性的序列 - 序列特征预测网络组成，该网络将字符嵌入映射到梅尔 - 比例谱图，然后是修改的WaveNet模型作为声码器以从这些谱图合成时域波形。我们的模型达到4.53的平均意见得分（MOS），相当于专业记录语音4.58的MOS。为了验证我们的设计选择，我们提出了我们系统关键组件的消融研究，并评估了使用mel谱图作为WaveNet的输入而不是语言，持续时间和F0特征的影响。我们进一步证明，使用紧凑的声学中间表示能够显着简化WaveNet架构。

##### URL
[http://arxiv.org/abs/1712.05884](http://arxiv.org/abs/1712.05884)

##### PDF
[http://arxiv.org/pdf/1712.05884](http://arxiv.org/pdf/1712.05884)

