---
layout: post
title: "Optimizing Channel Selection for Seizure Detection"
date: 2018-01-03 00:59:32
categories: arXiv_CV
tags: arXiv_CV RNN Deep_Learning Detection
author: Vinit Shah, Meysam Golmohammadi, Saeedeh Ziyabari, Eva Von Weltin, Iyad Obeid, Joseph Picone
mathjax: true
---

* content
{:toc}

##### Abstract
Interpretation of electroencephalogram (EEG) signals can be complicated by obfuscating artifacts. Artifact detection plays an important role in the observation and analysis of EEG signals. Spatial information contained in the placement of the electrodes can be exploited to accurately detect artifacts. However, when fewer electrodes are used, less spatial information is available, making it harder to detect artifacts. In this study, we investigate the performance of a deep learning algorithm, CNN-LSTM, on several channel configurations. Each configuration was designed to minimize the amount of spatial information lost compared to a standard 22-channel EEG. Systems using a reduced number of channels ranging from 8 to 20 achieved sensitivities between 33% and 37% with false alarms in the range of [38, 50] per 24 hours. False alarms increased dramatically (e.g., over 300 per 24 hours) when the number of channels was further reduced. Baseline performance of a system that used all 22 channels was 39% sensitivity with 23 false alarms. Since the 22-channel system was the only system that included referential channels, the rapid increase in the false alarm rate as the number of channels was reduced underscores the importance of retaining referential channels for artifact reduction. This cautionary result is important because one of the biggest differences between various types of EEGs administered is the type of referential channel used.

##### Abstract (translated by Google)
脑电图（EEG）信号的解读可能由于混淆伪像而变得复杂。伪影检测在脑电信号的观察和分析中起着重要的作用。包含在电极放置中的空间信息可以被利用来精确地检测伪影。然而，当使用较少的电极时，较少的空间信息可用，使得难以检测伪像。在这项研究中，我们研究了几种通道配置下的深度学习算法CNN-LSTM的性能。与标准的22通道脑电图相比，每种配置的设计都是为了尽量减少空间信息丢失。采用8-20个通道的数量减少的系统的灵敏度在33％到37％之间，误报率在每24小时[38，50]的范围内。当频道数目进一步减少时，虚假警报显着增加（例如每24小时超过300次）。使用全部22个通道的系统的基线性能是23％误报率的39％。由于22通道系统是唯一包含参考通道的系统，随着通道数量的减少误报率的快速增加突出了保留用于减少伪像的参考通道的重要性。这个谨慎的结果是重要的，因为各种类型的脑电图之间最大的区别之一是使用的参考通道的类型。

##### URL
[http://arxiv.org/abs/1801.02472](http://arxiv.org/abs/1801.02472)

##### PDF
[http://arxiv.org/pdf/1801.02472](http://arxiv.org/pdf/1801.02472)

