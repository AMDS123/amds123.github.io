---
layout: post
title: "Self-Attention Linguistic-Acoustic Decoder"
date: 2018-08-31 11:08:41
categories: arXiv_SD
tags: arXiv_SD Attention Inference RNN
author: Santiago Pascual, Antonio Bonafonte, Joan Serr&#xe0;
mathjax: true
---

* content
{:toc}

##### Abstract
The conversion from text to speech relies on the accurate mapping from linguistic to acoustic symbol sequences, for which current practice employs recurrent statistical models like recurrent neural networks. Despite the good performance of such models (in terms of low distortion in the generated speech), their recursive structure tends to make them slow to train and to sample from. In this work, we try to overcome the limitations of recursive structure by using a module based on the transformer decoder network, designed without recurrent connections but emulating them with attention and positioning codes. Our results show that the proposed decoder network is competitive in terms of distortion when compared to a recurrent baseline, whilst being significantly faster in terms of CPU inference time. On average, it increases Mel cepstral distortion between 0.1 and 0.3 dB, but it is over an order of magnitude faster on average. Fast inference is important for the deployment of speech synthesis systems on devices with restricted resources, like mobile phones or embedded systems, where speaking virtual assistants are gaining importance.

##### Abstract (translated by Google)
从文本到语音的转换依赖于从语言符号到声学符号序列的精确映射，当前的实践采用诸如递归神经网络的循环统计模型。尽管这些模型具有良好的性能（就所产生的语音中的低失真而言），但它们的递归结构往往使得它们训练和采样的速度变慢。在这项工作中，我们尝试通过使用基于变压器解码器网络的模块来克服递归结构的限制，该模块设计时没有循环连接，但使用注意和定位代码模拟它们。我们的结果表明，与循环基线相比，所提出的解码器网络在失真方面具有竞争力，同时在CPU推理时间方面明显更快。平均而言，它将Mel倒谱失真在0.1和0.3 dB之间增加，但平均快了一个数量级。快速推理对于在具有受限资源的设备上部署语音合成系统是重要的，例如移动电话或嵌入式系统，其中说话虚拟助理正变得越来越重要。

##### URL
[http://arxiv.org/abs/1808.10678](http://arxiv.org/abs/1808.10678)

##### PDF
[http://arxiv.org/pdf/1808.10678](http://arxiv.org/pdf/1808.10678)

