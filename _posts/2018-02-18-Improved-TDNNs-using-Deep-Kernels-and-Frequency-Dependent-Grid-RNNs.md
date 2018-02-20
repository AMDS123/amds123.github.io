---
layout: post
title: "Improved TDNNs using Deep Kernels and Frequency Dependent Grid-RNNs"
date: 2018-02-18 17:54:19
categories: arXiv_AI
tags: arXiv_AI Speech_Recognition CNN RNN Recognition
author: Florian Kreyssig, Chao Zhang, Philip Woodland
mathjax: true
---

* content
{:toc}

##### Abstract
Time delay neural networks (TDNNs) are an effective acoustic model for large vocabulary speech recognition. The strength of the model can be attributed to its ability to effectively model long temporal contexts. However, current TDNN models are relatively shallow, which limits the modelling capability. This paper proposes a method of increasing the network depth by deepening the kernel used in the TDNN temporal convolutions. The best performing kernel consists of three fully connected layers with a residual (ResNet) connection from the output of the first to the output of the third. The addition of spectro-temporal processing as the input to the TDNN in the form of a convolutional neural network (CNN) and a newly designed Grid-RNN was investigated. The Grid-RNN strongly outperforms a CNN if different sets of parameters for different frequency bands are used and can be further enhanced by using a bi-directional Grid-RNN. Experiments using the multi-genre broadcast (MGB3) English data (275h) show that deep kernel TDNNs reduces the word error rate (WER) by 6% relative and when combined with the frequency dependent Grid-RNN gives a relative WER reduction of 9%.

##### Abstract (translated by Google)
时间延迟神经网络（TDNN）是大型词汇语音识别的有效声学模型。模型的优势可以归因于其有效建模长时间背景的能力。但是，目前的TDNN模型相对较浅，限制了建模能力。本文提出了一种通过深化TDNN时间卷积中使用的内核来增加网络深度的方法。性能最好的内核由三个完全连接的层组成，剩下的（ResNet）连接从第一个输出到第三个输出。以卷积神经网络（CNN）和新设计的Grid-RNN的形式添加了光谱时间处理作为TDNN的输入。如果使用不同频带的不同参数集并且可以通过使用双向Grid-RNN来进一步增强，则Grid-RNN强烈胜过CNN。使用多类型的广播（MGB3）英语数据（275h）的实验表明，深内核TDNNs由6％的相对减少了字差错率（WER）和当与所述频率相关的网格RNN组合给出了相对WER减少了9％ 。

##### URL
[http://arxiv.org/abs/1802.06412](http://arxiv.org/abs/1802.06412)

##### PDF
[http://arxiv.org/pdf/1802.06412](http://arxiv.org/pdf/1802.06412)

