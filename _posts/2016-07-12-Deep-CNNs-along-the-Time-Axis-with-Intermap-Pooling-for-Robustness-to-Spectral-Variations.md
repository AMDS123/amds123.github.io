---
layout: post
title: "Deep CNNs along the Time Axis with Intermap Pooling for Robustness to Spectral Variations"
date: 2016-07-12 07:23:53
categories: arXiv_CL
tags: arXiv_CL CNN
author: Hwaran Lee, Geonmin Kim, Ho-Gyeong Kim, Sang-Hoon Oh, Soo-Young Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks (CNNs) with convolutional and pooling operations along the frequency axis have been proposed to attain invariance to frequency shifts of features. However, this is inappropriate with regard to the fact that acoustic features vary in frequency. In this paper, we contend that convolution along the time axis is more effective. We also propose the addition of an intermap pooling (IMP) layer to deep CNNs. In this layer, filters in each group extract common but spectrally variant features, then the layer pools the feature maps of each group. As a result, the proposed IMP CNN can achieve insensitivity to spectral variations characteristic of different speakers and utterances. The effectiveness of the IMP CNN architecture is demonstrated on several LVCSR tasks. Even without speaker adaptation techniques, the architecture achieved a WER of 12.7% on the SWB part of the Hub5'2000 evaluation test set, which is competitive with other state-of-the-art methods.

##### Abstract (translated by Google)
卷积神经网络（CNN）的卷积和池操作沿频率轴已经被提出来实现不变性的频移特征。然而，这对于声学特征在频率上变化的事实是不适当的。在本文中，我们认为沿着时间轴的卷积更有效。我们还建议在深层的CNN上增加一个跨层共享（IMP）层。在这一层中，每个组中的过滤器提取常见但频谱变化的特征，然后该层将每个组的特征映射进行汇集。因此，提出的IMP CNN可以实现对不同说话人和话语的频谱变化特征的不敏感性。 IMP CNN体系结构的有效性在几个LVCSR任务中得到证明。即使没有扬声器适配技术，该架构在Hub5'2000评估测试装置的SWB部分也达到了12.7％的WER，这与其他最先进的方法相比具有竞争力。

##### URL
[https://arxiv.org/abs/1606.03207](https://arxiv.org/abs/1606.03207)

##### PDF
[https://arxiv.org/pdf/1606.03207](https://arxiv.org/pdf/1606.03207)

