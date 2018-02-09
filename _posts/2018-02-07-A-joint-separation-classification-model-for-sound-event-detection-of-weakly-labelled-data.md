---
layout: post
title: "A joint separation-classification model for sound event detection of weakly labelled data"
date: 2018-02-07 21:57:10
categories: arXiv_SD
tags: arXiv_SD Segmentation Classification Detection
author: Qiuqiang Kong, Yong Xu, Wenwu Wang, Mark D. Plumbley
mathjax: true
---

* content
{:toc}

##### Abstract
Source separation (SS) aims to separate individual sources from an audio recording. Sound event detection (SED) aims to detect sound events from an audio recording. We propose a joint separation-classification (JSC) model trained only on weakly labelled audio data, that is, only the tags of an audio recording are known but the time of the events are unknown. First, we propose a separation mapping from the time-frequency (T-F) representation of an audio to the T-F segmentation masks of the audio events. Second, a classification mapping is built from each T-F segmentation mask to the presence probability of each audio event. In the source separation stage, sources of audio events and time of sound events can be obtained from the T-F segmentation masks. The proposed method achieves an equal error rate (EER) of 0.14 in SED, outperforming deep neural network baseline of 0.29. Source separation SDR of 8.08 dB is obtained by using global weighted rank pooling (GWRP) as probability mapping, outperforming the global max pooling (GMP) based probability mapping giving SDR at 0.03 dB. Source code of our work is published.

##### Abstract (translated by Google)
音源分离（SS）旨在将个别音源与音频录音分开。声音事件检测（SED）旨在检测来自录音的声音事件。我们提出一个联合分离分类（JSC）模型只训练弱标记的音频数据，也就是说，只有音频记录的标签是已知的，但事件的时间是未知的。首先，我们提出了从音频的时间频率（T-F）表示到音频事件的T-F分割掩模的分离映射。其次，从每个T-F分割掩模到每个音频事件的存在概率构建分类映射。在源分离阶段，音频事件的来源和声音事件的时间可以从T-F分割掩模获得。所提出的方法在SED中达到0.14的等误差率（EER），优于深度神经网络基线0.29。通过使用全局加权秩池（GWRP）作为概率映射获得8.08dB的源分离SDR，优于基于全局最大汇聚（GMP）的概率映射，使得SDR在0.03dB。我们工作的源代码已经发布。

##### URL
[http://arxiv.org/abs/1711.03037](http://arxiv.org/abs/1711.03037)

##### PDF
[http://arxiv.org/pdf/1711.03037](http://arxiv.org/pdf/1711.03037)

