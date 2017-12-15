---
layout: post
title: "Neural Machine Translation in Linear Time"
date: 2017-03-15 18:09:51
categories: arXiv_CL
tags: arXiv_CL Attention CNN Language_Model
author: Nal Kalchbrenner, Lasse Espeholt, Karen Simonyan, Aaron van den Oord, Alex Graves, Koray Kavukcuoglu
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel neural network for processing sequences. The ByteNet is a one-dimensional convolutional neural network that is composed of two parts, one to encode the source sequence and the other to decode the target sequence. The two network parts are connected by stacking the decoder on top of the encoder and preserving the temporal resolution of the sequences. To address the differing lengths of the source and the target, we introduce an efficient mechanism by which the decoder is dynamically unfolded over the representation of the encoder. The ByteNet uses dilation in the convolutional layers to increase its receptive field. The resulting network has two core properties: it runs in time that is linear in the length of the sequences and it sidesteps the need for excessive memorization. The ByteNet decoder attains state-of-the-art performance on character-level language modelling and outperforms the previous best results obtained with recurrent networks. The ByteNet also achieves state-of-the-art performance on character-to-character machine translation on the English-to-German WMT translation task, surpassing comparable neural translation models that are based on recurrent networks with attentional pooling and run in quadratic time. We find that the latent alignment structure contained in the representations reflects the expected alignment between the tokens.

##### Abstract (translated by Google)
我们提出了一个新的神经网络处理序列。 ByteNet是一个一维卷积神经网络，由两部分组成，一部分编码源序列，另一部分解码目标序列。两个网络部分通过在解码器的顶部堆叠解码器来连接，并保持序列的时间分辨率。为了解决源和目标的不同长度，我们引入了解码器在编码器的表示上动态展开的有效机制。 ByteNet使用卷积图层中的膨胀来增加其接受范围。由此产生的网络具有两个核心属性：它在时间上运行，在序列长度上是线性的，并且避免了过度记忆的需要。 ByteNet解码器在字符级语言建模方面达到了最先进的性能，并且胜过了经常性网络获得的以前最好的结果。 ByteNet还在英语到德语的WMT翻译任务上实现了字符到字符机器翻译方面的最新性能，超越了类似的神经翻译模型，该模型基于循环网络，具有注意力集中和二次运行。我们发现包含在表示中的潜在对齐结构反映了令牌之间的预期对齐。

##### URL
[https://arxiv.org/abs/1610.10099](https://arxiv.org/abs/1610.10099)

##### PDF
[https://arxiv.org/pdf/1610.10099](https://arxiv.org/pdf/1610.10099)

