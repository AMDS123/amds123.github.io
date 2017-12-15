---
layout: post
title: "Learning Multiscale Features Directly From Waveforms"
date: 2016-04-05 14:17:09
categories: arXiv_SD
tags: arXiv_SD Speech_Recognition CNN Deep_Learning Recognition
author: Zhenyao Zhu, Jesse H. Engel, Awni Hannun
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning has dramatically improved the performance of speech recognition systems through learning hierarchies of features optimized for the task at hand. However, true end-to-end learning, where features are learned directly from waveforms, has only recently reached the performance of hand-tailored representations based on the Fourier transform. In this paper, we detail an approach to use convolutional filters to push past the inherent tradeoff of temporal and frequency resolution that exists for spectral representations. At increased computational cost, we show that increasing temporal resolution via reduced stride and increasing frequency resolution via additional filters delivers significant performance improvements. Further, we find more efficient representations by simultaneously learning at multiple scales, leading to an overall decrease in word error rate on a difficult internal speech test set by 20.7% relative to networks with the same number of parameters trained on spectrograms.

##### Abstract (translated by Google)
深度学习通过学习对于手头任务优化的功能层次，显着提高了语音识别系统的性能。然而，直接从波形中学习特征的真正的端到端学习最近才基于傅立叶变换达到了手工定制的表现。在本文中，我们详细介绍了一种使用卷积滤波器来推进频谱表示中存在的时间和频率分辨率的内在折衷的方法。随着计算成本的增加，我们展示了通过减少步幅增加时间分辨率和通过附加滤波器提高频率分辨率可以显着提高性能。此外，通过同时学习多个尺度，我们发现更有效的表示，导致相对于在谱图上训练相同参数数量的网络，困难的内部语音测试集中的词汇错误率整体下降20.7％。

##### URL
[https://arxiv.org/abs/1603.09509](https://arxiv.org/abs/1603.09509)

##### PDF
[https://arxiv.org/pdf/1603.09509](https://arxiv.org/pdf/1603.09509)

