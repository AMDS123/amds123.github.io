---
layout: post
title: "Musical Instrument Separation on Shift-Invariant Spectrograms via Stochastic Dictionary Learning"
date: 2018-06-01 10:28:50
categories: arXiv_SD
tags: arXiv_SD Optimization
author: S&#xf6;ren Schulze, Emily J. King
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a method for the blind separation of audio signals from musical instruments. While the approach of applying non-negative matrix factorization (NMF) has been studied in many papers, it does not make use of the pitch-invariance that instruments exhibit. This limitation can be overcome by using tensor factorization, in which context the use of log-frequency spectrograms was initiated, but this still requires the specific tuning of the instruments to be hard-coded into the algorithm. We develop a time-frequency representation that is both shift-invariant and frequency-aligned, with a variant that can also be used for wideband signals. Our separation algorithm exploits this shift-invariance in order to find patterns of peaks related to specific instruments, while non-linear optimization enables it to represent arbitrary frequencies and incorporate inharmonicity, and the reasonability of the representation is ensured by a sparsity condition. The relative amplitudes of the harmonics are saved in a dictionary, which is trained via a modified version of ADAM. For a realistic monaural piece with acoustic recorder and violin, we achieve qualitatively good separation with a signal-to-distortion ratio (SDR) of 12.7 dB, a signal-to-interference ratio (SIR) of 27.0 dB, and a signal-to-artifacts ratio (SAR) of 12.9 dB, averaged.

##### Abstract (translated by Google)
我们提出了一种从乐器盲分离音频信号的方法。尽管应用非负矩阵分解（NMF）的方法已经在许多论文中进行了研究，但它没有利用仪器表现出的音调不变性。这种限制可以通过使用张量分解来克服，在这种情况下，开始使用对数频谱图，但是这仍需要将仪器的特定调谐硬编码到算法中。我们开发了一种时移频率表示法，该表示法既是移位不变的，又是频率对齐的，其变体也可以用于宽带信号。我们的分离算法利用这种移位不变性来寻找与特定仪器相关的峰值模式，而非线性优化使其能够表示任意频率并纳入不和谐性，并且由稀疏性条件来确保表示的合理性。谐波的相对幅度保存在字典中，该字典通过ADAM的修改版本进行训练。对于带有录音机和小提琴的现实单声道乐曲，我们实现了12.7 dB的信号与失真比（SDR），27.0 dB的信号与干扰比（SIR）以及信号与信号之间的良好分离 - 文物比率（SAR）为12.9 dB，平均值。

##### URL
[http://arxiv.org/abs/1806.00273](http://arxiv.org/abs/1806.00273)

##### PDF
[http://arxiv.org/pdf/1806.00273](http://arxiv.org/pdf/1806.00273)

