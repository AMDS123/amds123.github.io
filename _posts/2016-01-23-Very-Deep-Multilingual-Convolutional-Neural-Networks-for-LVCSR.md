---
layout: post
title: "Very Deep Multilingual Convolutional Neural Networks for LVCSR"
date: 2016-01-23 18:18:58
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition CNN Recognition
author: Tom Sercu, Christian Puhrsch, Brian Kingsbury, Yann LeCun
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks (CNNs) are a standard component of many current state-of-the-art Large Vocabulary Continuous Speech Recognition (LVCSR) systems. However, CNNs in LVCSR have not kept pace with recent advances in other domains where deeper neural networks provide superior performance. In this paper we propose a number of architectural advances in CNNs for LVCSR. First, we introduce a very deep convolutional network architecture with up to 14 weight layers. There are multiple convolutional layers before each pooling layer, with small 3x3 kernels, inspired by the VGG Imagenet 2014 architecture. Then, we introduce multilingual CNNs with multiple untied layers. Finally, we introduce multi-scale input features aimed at exploiting more context at negligible computational cost. We evaluate the improvements first on a Babel task for low resource speech recognition, obtaining an absolute 5.77% WER improvement over the baseline PLP DNN by training our CNN on the combined data of six different languages. We then evaluate the very deep CNNs on the Hub5'00 benchmark (using the 262 hours of SWB-1 training data) achieving a word error rate of 11.8% after cross-entropy training, a 1.4% WER improvement (10.6% relative) over the best published CNN result so far.

##### Abstract (translated by Google)
卷积神经网络（CNN）是许多当前最先进的大型词汇连续语音识别（LVCSR）系统的标准组件。然而，LVCSR中的CNN并没有跟上其他领域的最新进展，其中更深的神经网络提供了更好的性能。在本文中，我们提出了一些在CNN中用于LVCSR的架构进展。首先，我们介绍一个非常深的卷积网络架构，最多有14个权重层。在每个池层之前有多个卷积层，小的3x3内核受VGG Imagenet 2014架构的启发。然后，我们引入具有多个无缝层的多语言CNN。最后，我们引入多尺度输入特征，旨在以可忽略的计算成本开发更多的上下文。我们首先评估Babel任务中对低资源语音识别的改进，通过对6种不同语言的组合数据进行CNN训练，获得比基线PLP DNN绝对5.77％的WER改进。然后，我们在Hub5'00基准（使用SWB-1训练数据的262小时）上评估非常深的CNN，在交叉熵训练后达到11.8％的字错误率，WER改善1.4％（相对于10.6％）迄今为止发表的最好的CNN结果。

##### URL
[https://arxiv.org/abs/1509.08967](https://arxiv.org/abs/1509.08967)

##### PDF
[https://arxiv.org/pdf/1509.08967](https://arxiv.org/pdf/1509.08967)

