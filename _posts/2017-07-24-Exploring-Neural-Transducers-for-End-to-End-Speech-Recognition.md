---
layout: post
title: "Exploring Neural Transducers for End-to-End Speech Recognition"
date: 2017-07-24 06:05:21
categories: arXiv_CL
tags: arXiv_CL Attention Speech_Recognition RNN Language_Model Recognition
author: Eric Battenberg, Jitong Chen, Rewon Child, Adam Coates, Yashesh Gaur, Yi Li, Hairong Liu, Sanjeev Satheesh, David Seetapun, Anuroop Sriram, Zhenyao Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we perform an empirical comparison among the CTC, RNN-Transducer, and attention-based Seq2Seq models for end-to-end speech recognition. We show that, without any language model, Seq2Seq and RNN-Transducer models both outperform the best reported CTC models with a language model, on the popular Hub5'00 benchmark. On our internal diverse dataset, these trends continue - RNNTransducer models rescored with a language model after beam search outperform our best CTC models. These results simplify the speech recognition pipeline so that decoding can now be expressed purely as neural network operations. We also study how the choice of encoder architecture affects the performance of the three models - when all encoder layers are forward only, and when encoders downsample the input representation aggressively.

##### Abstract (translated by Google)
在这项工作中，我们对CTC，RNN-Transducer和基于注意力的Seq2Seq模型进行了端到端语音识别的实证比较。我们发现，在没有任何语言模型的情况下，Seq2Seq和RNN-Transducer模型在流行的Hub5'00基准测试中的表现都优于具有语言模型的最佳报告CTC模型。在我们内部的不同数据集上，这些趋势继续下去 -  RNNTransducer模型在波束搜索之后胜过了我们最好的CTC模型后，重新用语言模型重新定义了模型。这些结果简化了语音识别流水线，因此现在可以将解码纯粹地表示为神经网络操作。我们还研究了编码器体系结构的选择如何影响三种模型的性能 - 当所有的编码器层仅仅是前向的，并且编码器积极地对输入表示进行下采样时。

##### URL
[https://arxiv.org/abs/1707.07413](https://arxiv.org/abs/1707.07413)

##### PDF
[https://arxiv.org/pdf/1707.07413](https://arxiv.org/pdf/1707.07413)

