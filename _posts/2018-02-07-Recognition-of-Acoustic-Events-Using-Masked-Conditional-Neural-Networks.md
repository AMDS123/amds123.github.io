---
layout: post
title: "Recognition of Acoustic Events Using Masked Conditional Neural Networks"
date: 2018-02-07 19:58:50
categories: arXiv_SD
tags: arXiv_SD Sparse CNN Relation Recognition
author: Fady Medhat, David Chesmore, John Robinson
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic feature extraction using neural networks has accomplished remarkable success for images, but for sound recognition, these models are usually modified to fit the nature of the multi-dimensional temporal representation of the audio signal in spectrograms. This may not efficiently harness the time-frequency representation of the signal. The ConditionaL Neural Network (CLNN) takes into consideration the interrelation between the temporal frames, and the Masked ConditionaL Neural Network (MCLNN) extends upon the CLNN by forcing a systematic sparseness over the network's weights using a binary mask. The masking allows the network to learn about frequency bands rather than bins, mimicking a filterbank used in signal transformations such as MFCC. Additionally, the Mask is designed to consider various combinations of features, which automates the feature hand-crafting process. We applied the MCLNN for the Environmental Sound Recognition problem using the Urbansound8k, YorNoise, ESC-10 and ESC-50 datasets. The MCLNN have achieved competitive performance compared to state-of-the-art Convolutional Neural Networks and hand-crafted attempts.

##### Abstract (translated by Google)
使用神经网络的自动特征提取已经在图像上取得了显着的成功，但是对于声音识别，通常对这些模型进行修改以适应音频信号的多维时间表示在频谱图中的性质。这可能不能有效地利用信号的时频表示。条件神经网络（CLNN）考虑了时间帧之间的相互关系，并且掩蔽条件神经网络（MCLNN）通过使用二进制掩码在网络权重上强制系统稀疏而延伸到CLNN上。屏蔽允许网络学习频带而不是箱，模仿在诸如MFCC的信号转换中使用的滤波器组。此外，面具设计考虑功能的各种组合，自动功能手工制作过程。我们使用Urbansound8k，YorNoise，ESC-10和ESC-50数据集应用MCLNN进行环境声音识别问题。与最先进的卷积神经网络和手工尝试相比，MCLNN已经实现了有竞争力的性能。

##### URL
[http://arxiv.org/abs/1802.02617](http://arxiv.org/abs/1802.02617)

##### PDF
[http://arxiv.org/pdf/1802.02617](http://arxiv.org/pdf/1802.02617)

