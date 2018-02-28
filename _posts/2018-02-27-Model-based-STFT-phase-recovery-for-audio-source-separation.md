---
layout: post
title: "Model-based STFT phase recovery for audio source separation"
date: 2018-02-27 09:09:03
categories: arXiv_SD
tags: arXiv_SD
author: Paul Magron, Roland Badeau, Bertrand David
mathjax: true
---

* content
{:toc}

##### Abstract
For audio source separation applications, it is common to estimate the magnitude of the short-time Fourier transform (STFT) of each source. In order to further synthesizing time-domain signals, it is necessary to recover the phase of the corresponding complex-valued STFT. Most authors in this field choose a Wiener-like filtering approach which boils down to using the phase of the original mixture. In this paper, a different standpoint is adopted. Many music events are partially composed of slowly varying sinusoids and the STFT phase increment over time of those frequency components takes a specific form. This allows phase recovery by an unwrapping technique once a short-term frequency estimate has been obtained. Herein, a novel iterative source separation procedure is proposed which builds upon these results. It consists in minimizing the mixing error by means of the auxiliary function method. This procedure is initialized by exploiting the unwrapping technique in order to generate estimates that benefit from a temporal continuity property. Experiments conducted on realistic music pieces show that, given accurate magnitude estimates, this procedure outperforms the state-of-the-art consistent Wiener filter.

##### Abstract (translated by Google)
对于音频源分离应用，估计每个源的短时傅立叶变换（STFT）的大小是常见的。为了进一步合成时域信号，有必要恢复相应的复数值STFT的相位。该领域的大多数作者选择类似维纳的滤波方法，归结为使用原始混合物的相位。在本文中，采用了不同的观点。许多音乐事件部分由缓慢变化的正弦曲线组成，并且随着时间的推移，这些频率分量的STFT相位增量采取特定形式。一旦获得短期频率估计，这允许通过解缠技术进行相位恢复。在此，提出了一种基于这些结果的新型迭代源分离程序。它包括通过辅助功能方法来最小化混合误差。该过程通过利用展开技术来初始化，以便生成从时间连续性特性中受益的估计。在逼真的音乐作品上进行的实验表明，如果给出准确的幅度估计值，则此过程将胜过最先进的一致维纳滤波器。

##### URL
[http://arxiv.org/abs/1608.01953](http://arxiv.org/abs/1608.01953)

##### PDF
[http://arxiv.org/pdf/1608.01953](http://arxiv.org/pdf/1608.01953)

