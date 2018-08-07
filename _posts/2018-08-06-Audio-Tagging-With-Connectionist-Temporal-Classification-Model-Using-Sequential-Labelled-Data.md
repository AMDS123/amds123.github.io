---
layout: post
title: "Audio Tagging With Connectionist Temporal Classification Model Using Sequential Labelled Data"
date: 2018-08-06 14:40:31
categories: arXiv_CL
tags: arXiv_CL CNN RNN Classification
author: Yuanbo Hou, Qiuqiang Kong, Shengchen Li
mathjax: true
---

* content
{:toc}

##### Abstract
Audio tagging aims to predict one or several labels in an audio clip. Many previous works use weakly labelled data (WLD) for audio tagging, where only presence or absence of sound events is known, but the order of sound events is unknown. To use the order information of sound events, we propose sequential labelled data (SLD), where both the presence or absence and the order information of sound events are known. To utilize SLD in audio tagging, we propose a Convolutional Recurrent Neural Network followed by a Connectionist Temporal Classification (CRNN-CTC) objective function to map from an audio clip spectrogram to SLD. Experiments show that CRNN-CTC obtains an Area Under Curve (AUC) score of 0.986 in audio tagging, outperforming the baseline CRNN of 0.908 and 0.815 with Max Pooling and Average Pooling, respectively. In addition, we show CRNN-CTC has the ability to predict the order of sound events in an audio clip.

##### Abstract (translated by Google)
音频标记旨在预测音频剪辑中的一个或多个标签。许多以前的作品使用弱标记数据（WLD）进行音频标记，其中只有声音事件的存在或不存在，但声音事件的顺序是未知的。为了使用声音事件的顺序信息，我们提出顺序标记数据（SLD），其中声音事件的存在或不存在和顺序信息都是已知的。为了在音频标签中利用SLD，我们提出了卷积递归神经网络，然后是连接主义时间分类（CRNN-CTC）目标函数，以从音频剪辑频谱图映射到SLD。实验表明，CRNN-CTC在音频标签中获得的曲线下面积（AUC）得分为0.986，优于基线CRNN分别为0.908和0.815（最大池化和平均合并）。此外，我们还展示了CRNN-CTC能够预测音频片段中声音事件的顺序。

##### URL
[http://arxiv.org/abs/1808.01935](http://arxiv.org/abs/1808.01935)

##### PDF
[http://arxiv.org/pdf/1808.01935](http://arxiv.org/pdf/1808.01935)

