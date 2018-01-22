---
layout: post
title: "Epoch-Synchronous Overlap-Add for Time- and Pitch-Scale Modification of Speech Signals"
date: 2018-01-19 17:05:59
categories: arXiv_SD
tags: arXiv_SD Embedding
author: Sunil Rudresh, Aditya Vasisht, Karthika Vijayan, Chandra Sekhar Seelamantula
mathjax: true
---

* content
{:toc}

##### Abstract
Time- and pitch-scale modifications of speech signals find important applications in speech synthesis, playback systems, voice conversion, learning/hearing aids, etc.. There is a requirement for computationally efficient and real-time implementable algorithms. In this paper, we propose a high quality and computationally efficient time- and pitch-scaling methodology based on the glottal closure instants (GCIs) or epochs in speech signals. The proposed algorithm, termed as epoch-synchronous overlap-add time/pitch-scaling (ESOLA-TS/PS), segments speech signals into overlapping short-time frames and then the adjacent frames are aligned with respect to the epochs and the frames are overlap-added to synthesize time-scale modified speech. Pitch scaling is achieved by resampling the time-scaled speech by a desired sampling factor. We also propose a concept of epoch embedding into speech signals, which facilitates the identification and time-stamping of samples corresponding to epochs and using them for time/pitch-scaling to multiple scaling factors whenever desired, thereby contributing to faster and efficient implementation. The results of perceptual evaluation tests reported in this paper indicate the superiority of ESOLA over state-of-the-art techniques. ESOLA significantly outperforms the conventional pitch synchronous overlap-add (PSOLA) techniques in terms of perceptual quality and intelligibility of the modified speech. Unlike the waveform similarity overlap-add (WSOLA) or synchronous overlap-add (SOLA) techniques, the ESOLA technique has the capability to do exact time-scaling of speech with high quality to any desired modification factor within a range of 0.5 to 2. Compared to synchronous overlap-add with fixed synthesis (SOLAFS), the ESOLA is computationally advantageous and at least three times faster.

##### Abstract (translated by Google)
语音信号的时间和音调尺度修改在语音合成，回放系统，语音转换，学习/助听器等中找到重要的应用。需要计算高效和实时可实现的算法。在本文中，我们提出了一个基于声门闭合时刻（GCIs）或语音信号时代的高质量和计算有效的时间和音高缩放方法。所提出的算法被称为历元同步重叠相加时间/音高缩放（ESOLA-TS / PS），将语音信号分割成重叠的短时间帧，然后相邻帧相对于历元对齐，并且帧是重叠加合成时标修改后的语音。音调缩放是通过将时间缩放语音重新采样所需的采样因子来实现的。我们还提出了一种将时期嵌入到语音信号中的概念，这有助于识别和时间戳对应于时期的样本，并且在需要时使用它们对多个缩放因子进行时间/间距缩放，从而有助于更快和有效地实施。本文报道的感知评估测试结果表明，ESOLA优于最先进的技术。 ESOLA在修改后的语音的感知质量和可理解性方面明显优于传统的基音同步重叠相加（PSOLA）技术。与波形相似性叠加（WSOLA）或同步叠加（SOLA）技术不同的是，ESOLA技术能够以0.5到2的范围内的任何期望的修正因子对高质量的语音进行精确的时间缩放。与具有固定合成（SOLAFS）的同步叠加相比，ESOLA在计算上是有利的并且至少快三倍。

##### URL
[http://arxiv.org/abs/1801.06492](http://arxiv.org/abs/1801.06492)

##### PDF
[http://arxiv.org/pdf/1801.06492](http://arxiv.org/pdf/1801.06492)

