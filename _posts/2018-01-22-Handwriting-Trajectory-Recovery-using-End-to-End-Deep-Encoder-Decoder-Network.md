---
layout: post
title: "Handwriting Trajectory Recovery using End-to-End Deep Encoder-Decoder Network"
date: 2018-01-22 17:25:05
categories: arXiv_CV
tags: arXiv_CV CNN RNN Recognition
author: Ayan Kumar Bhunia, Abir Bhowmick, Ankan Kumar Bhunia, Aishik Konwer, Prithaj Banerjee, Partha Pratim Roy, Umapada Pal
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we introduce a novel technique to recover the pen trajectory of offline characters which is a crucial step for handwritten character recognition. Generally, online acquisition approach has more advantage than its offline counterpart as the online technique keeps track of the pen movement. Hence, pen tip trajectory retrieval from offline text can bridge the gap between online and offline methods. Our proposed framework employs sequence to sequence model which consists of an encoder-decoder LSTM module. Our encoder module consists of Convolutional LSTM network, which takes an offline character image as the input and encodes the feature sequence to a hidden representation. The output of the encoder is fed to a decoder LSTM and we get the successive coordinate points from every time step of the decoder LSTM. Although the sequence to sequence model is a popular paradigm in various computer vision and language translation tasks, the main contribution of our work lies in designing an end-to-end network for a decade old popular problem in Document Image Analysis community. Tamil, Telugu and Devanagari characters of LIPI Toolkit dataset are used for our experiments. Our proposed method has achieved superior performance compared to the other conventional approaches.

##### Abstract (translated by Google)
在本文中，我们引入了一种新的技术来恢复离线字符的笔轨迹，这是手写字符识别的关键步骤。一般来说，在线技术跟踪笔的移动，在线获取方式比线下技术具有更多的优势。因此，离线文本的笔尖轨迹检索可以弥补在线和离线方法之间的差距。我们提出的框架采用序列模型，其中包括编码器 - 解码器LSTM模块。我们的编码器模块由卷积LSTM网络组成，该网络以离线字符图像为输入，并将特征序列编码为隐藏表示。编码器的输出被馈送到解码器LSTM，并且从解码器LSTM的每个时间步获得连续的坐标点。虽然顺序模型是各种计算机视觉和语言翻译任务中流行的范例，但我们工作的主要贡献在于为文档图像分析社区设计了一个十年前流行问题的端到端网络。我们的实验使用了LIPI Toolkit数据集的泰米尔语，泰卢固语和梵文字符。与其他传统方法相比，我们提出的方法已经实现了优越的性能。

##### URL
[https://arxiv.org/abs/1801.07211](https://arxiv.org/abs/1801.07211)

##### PDF
[https://arxiv.org/pdf/1801.07211](https://arxiv.org/pdf/1801.07211)

