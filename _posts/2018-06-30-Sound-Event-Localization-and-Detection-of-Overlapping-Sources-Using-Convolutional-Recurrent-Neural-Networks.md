---
layout: post
title: "Sound Event Localization and Detection of Overlapping Sources Using Convolutional Recurrent Neural Networks"
date: 2018-06-30 06:05:20
categories: arXiv_SD
tags: arXiv_SD CNN RNN Classification Detection
author: Sharath Adavanne, Archontis Politis, Joonas Nikunen, Tuomas Virtanen
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a convolutional recurrent neural network for joint sound event localization and detection (SELD) of multiple overlapping sound events in three-dimensional (3D) space. The proposed network takes a sequence of consecutive spectrogram time-frames as input and maps it to two outputs in parallel. As the first output, the sound event detection (SED) is performed as a multi-label multi-class classification task on each time-frame producing temporal activity for all the sound event classes. As the second output, localization is performed by estimating the 3D Cartesian coordinates of the direction-of-arrival (DOA) for each sound event class using multi-class regression. The proposed method is able to associate multiple DOAs with respective sound event labels and further track this association with respect to time. The proposed method uses separately the phase and magnitude component of the spectrogram calculated on each audio channel as the feature, thereby avoiding any method- and array-specific feature extraction. The method is evaluated on five Ambisonic and two circular array format datasets with different overlapping sound events in anechoic, reverberant and real-life scenarios. The proposed method is compared with two SED, three DOA estimation, and one SELD baselines. The results show that the proposed method is generic to array structures, robust to unseen DOA labels, reverberation, and low SNR scenarios. The proposed joint estimation of DOA and SED in comparison to the respective standalone baselines resulted in a consistently higher recall of the estimated number of DOAs across datasets.

##### Abstract (translated by Google)
在本文中，我们提出了一种卷积递归神经网络，用于三维（3D）空间中多个重叠声音事件的联合声音事件定位和检测（SELD）。所提出的网络将一系列连续的频谱图时间帧作为输入并将其并行地映射到两个输出。作为第一输出，声音事件检测（SED）作为多标签多类别分类任务在每个时间帧上执行，产生所有声音事件类别的时间活动。作为第二输出，通过使用多类回归估计每个声音事件类的到达方向（DOA）的3D笛卡尔坐标来执行定位。所提出的方法能够将多个DOA与相应的声音事件标签相关联，并进一步跟踪该时间关联。所提出的方法分别使用在每个音频通道上计算的频谱图的相位和幅度分量作为特征，从而避免任何特定于方法和阵列的特征提取。该方法在五个Ambisonic和两个圆形阵列格式数据集上进行评估，在消声，混响和现实场景中具有不同的重叠声音事件。将所提出的方法与两个SED，三个DOA估计和一个SELD基线进行比较。结果表明，所提出的方法对于阵列结构是通用的，对于看不见的DOA标签，混响和低SNR场景是鲁棒的。建议的DOA和SED联合评估与相应的独立基线相比，导致数据集中估计的DOA数量的回忆率始终更高。

##### URL
[http://arxiv.org/abs/1807.00129](http://arxiv.org/abs/1807.00129)

##### PDF
[http://arxiv.org/pdf/1807.00129](http://arxiv.org/pdf/1807.00129)

