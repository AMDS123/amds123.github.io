---
layout: post
title: "Resource aware design of a deep convolutional-recurrent neural network for speech recognition through audio-visual sensor fusion"
date: 2018-03-13 14:35:00
categories: arXiv_CV
tags: arXiv_CV Attention Speech_Recognition CNN RNN Recognition
author: Matthijs Van keirsbilck, Bert Moons, Marian Verhelst
mathjax: true
---

* content
{:toc}

##### Abstract
Today's Automatic Speech Recognition systems only rely on acoustic signals and often don't perform well under noisy conditions. Performing multi-modal speech recognition - processing acoustic speech signals and lip-reading video simultaneously - significantly enhances the performance of such systems, especially in noisy environments. This work presents the design of such an audio-visual system for Automated Speech Recognition, taking memory and computation requirements into account. First, a Long-Short-Term-Memory neural network for acoustic speech recognition is designed. Second, Convolutional Neural Networks are used to model lip-reading features. These are combined with an LSTM network to model temporal dependencies and perform automatic lip-reading on video. Finally, acoustic-speech and visual lip-reading networks are combined to process acoustic and visual features simultaneously. An attention mechanism ensures performance of the model in noisy environments. This system is evaluated on the TCD-TIMIT 'lipspeaker' dataset for audio-visual phoneme recognition with clean audio and with additive white noise at an SNR of 0dB. It achieves 75.70% and 58.55% phoneme accuracy respectively, over 14 percentage points better than the state-of-the-art for all noise levels.

##### Abstract (translated by Google)
今天的自动语音识别系统只依赖声音信号，并且在噪声条件下通常效果不佳。执行多模式语音识别 - 同时处理声音语音信号和唇读视频 - 显着增强了此类系统的性能，特别是在嘈杂的环境中。这项工作介绍了这种用于自动语音识别的视听系统的设计，考虑到了记忆和计算要求。首先，设计了一个用于声学语音识别的长短期记忆神经网络。其次，卷积神经网络被用来模拟唇读特征。这些与LSTM网络相结合来模拟时间依赖性，并对视频进行自动唇读。最后，将声学语音和视觉唇读网络结合在一起，同时处理声学和视觉特征。注意机制可确保模型在嘈杂环境中的性能。该系统在TCD-TIMIT的'lipspeaker'数据集上进行评估，用于使用清晰音频和具有0dB信噪比的附加白噪声进行视听音素识别。对于所有噪音水平，它分别达到75.70％和58.55％的音素准确度，比最先进的技术要好14个百分点。

##### URL
[http://arxiv.org/abs/1803.04840](http://arxiv.org/abs/1803.04840)

##### PDF
[http://arxiv.org/pdf/1803.04840](http://arxiv.org/pdf/1803.04840)

