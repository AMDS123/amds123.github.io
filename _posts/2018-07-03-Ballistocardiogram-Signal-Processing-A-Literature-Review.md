---
layout: post
title: "Ballistocardiogram Signal Processing: A Literature Review"
date: 2018-07-03 01:57:36
categories: arXiv_CV
tags: arXiv_CV Review
author: Ibrahim Sadek
mathjax: true
---

* content
{:toc}

##### Abstract
Time-domain algorithms are focused on detecting local maxima or local minima using a moving window, and therefore finding the interval between the dominant J-peaks of ballistocardiogram (BCG) signal. However, this approach has many limitations due to the nonlinear and nonstationary behavior of the BCG signal. This is because the BCG signal does not display consistent J-peaks, which can usually be the case for overnight, in-home monitoring, particularly with frail elderly. Additionally, its accuracy will be undoubtedly affected by motion artifacts. Second, frequency-domain algorithms do not provide information about interbeat intervals. Nevertheless, they can provide information about heart rate variability. This is usually done by taking the fast Fourier transform or the inverse Fourier transform of the logarithm of the estimated spectrum, i.e., cepstrum of the signal using a sliding window. Thereafter, the dominant frequency is obtained in a particular frequency range. The limit of these algorithms is that the peak in the spectrum may get wider and multiple peaks may appear, which might cause a problem in measuring the vital signs. At last, the objective of wavelet-domain algorithms is to decompose the signal into different components, hence the component which shows an agreement with the vital signs can be selected i.e., the selected component contains only information about the heart cycles or respiratory cycles, respectively. An empirical mode decomposition is an alternative approach to wavelet decomposition, and it is also a very suitable approach to cope with nonlinear and nonstationary signals such as cardiorespiratory signals. Apart from the above-mentioned algorithms, machine learning approaches have been implemented for measuring heartbeats. However, manual labeling of training data is a restricting property.

##### Abstract (translated by Google)
时域算法专注于使用移动窗口检测局部最大值或局部最小值，并因此找到心冲击描记图（BCG）信号的主要J峰值之间的间隔。然而，由于BCG信号的非线性和非平稳行为，该方法具有许多限制。这是因为BCG信号不显示一致的J峰，这通常可以是夜间家庭监测的情况，特别是对于体弱的老年人。此外，它的准确性无疑会受到运动伪影的影响。其次，频域算法不提供有关间隔间隔的信息。然而，他们可以提供有关心率变异性的信息。这通常通过使用滑动窗口对估计的频谱的对数（即信号的倒谱）进行快速傅立叶变换或逆傅里叶变换来完成。此后，在特定频率范围内获得主频率。这些算法的极限是光谱中的峰值可能变宽并且可能出现多个峰值，这可能导致测量生命体征的问题。最后，小波域算法的目的是将信号分解成不同的分量，因此可以选择与生命体征一致的分量，即，所选择的分量仅包含关于心动周期或呼吸周期的信息。 。经验模式分解是小波分解的替代方法，并且它也是处理诸如心肺呼吸信号的非线性和非平稳信号的非常合适的方法。除了上述算法之外，还实现了用于测量心跳的机器学习方法。但是，手动标记训练数据是一种限制性属性。

##### URL
[https://arxiv.org/abs/1807.00951](https://arxiv.org/abs/1807.00951)

##### PDF
[https://arxiv.org/pdf/1807.00951](https://arxiv.org/pdf/1807.00951)

