---
layout: post
title: "Deconvolution-Based Global Decoding for Neural Machine Translation"
date: 2018-06-10 17:05:31
categories: arXiv_CL
tags: arXiv_CL NMT RNN Prediction
author: Junyang Lin, Xu Sun, Xuancheng Ren, Shuming Ma, Jinsong Su, Qi Su
mathjax: true
---

* content
{:toc}

##### Abstract
A great proportion of sequence-to-sequence (Seq2Seq) models for Neural Machine Translation (NMT) adopt Recurrent Neural Network (RNN) to generate translation word by word following a sequential order. As the studies of linguistics have proved that language is not linear word sequence but sequence of complex structure, translation at each step should be conditioned on the whole target-side context. To tackle the problem, we propose a new NMT model that decodes the sequence with the guidance of its structural prediction of the context of the target sequence. Our model generates translation based on the structural prediction of the target-side context so that the translation can be freed from the bind of sequential order. Experimental results demonstrate that our model is more competitive compared with the state-of-the-art methods, and the analysis reflects that our model is also robust to translating sentences of different lengths and it also reduces repetition with the instruction from the target-side context for decoding.

##### Abstract (translated by Google)
用于神经机器翻译（NMT）的序列到序列（Seq2Seq）模型的很大一部分采用递归神经网络（RNN）来按顺序依次生成翻译。由于语言学的研究已经证明，语言不是线性的单词序列，而是复杂结构的序列，每一步的翻译都应以整个目标语境为条件。为了解决这个问题，我们提出了一个新的NMT模型，该模型在对目标序列的上下文进行结构预测的指导下对序列进行解码。我们的模型根据目标端上下文的结构预测生成翻译，以便翻译可以从顺序的绑定中解脱出来。实验结果表明，与最先进的方法相比，我们的模型更具竞争力，并且分析表明，我们的模型对于翻译不同长度的句子也是强健的，并且它还减少了来自目标侧的指令的重复上下文进行解码。

##### URL
[http://arxiv.org/abs/1806.03692](http://arxiv.org/abs/1806.03692)

##### PDF
[http://arxiv.org/pdf/1806.03692](http://arxiv.org/pdf/1806.03692)

