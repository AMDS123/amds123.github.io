---
layout: post
title: "Character-Level Incremental Speech Recognition with Recurrent Neural Networks"
date: 2016-01-28 11:03:05
categories: arXiv_SD
tags: arXiv_SD Speech_Recognition RNN Classification Language_Model Recognition
author: Kyuyeon Hwang, Wonyong Sung
mathjax: true
---

* content
{:toc}

##### Abstract
In real-time speech recognition applications, the latency is an important issue. We have developed a character-level incremental speech recognition (ISR) system that responds quickly even during the speech, where the hypotheses are gradually improved while the speaking proceeds. The algorithm employs a speech-to-character unidirectional recurrent neural network (RNN), which is end-to-end trained with connectionist temporal classification (CTC), and an RNN-based character-level language model (LM). The output values of the CTC-trained RNN are character-level probabilities, which are processed by beam search decoding. The RNN LM augments the decoding by providing long-term dependency information. We propose tree-based online beam search with additional depth-pruning, which enables the system to process infinitely long input speech with low latency. This system not only responds quickly on speech but also can dictate out-of-vocabulary (OOV) words according to pronunciation. The proposed model achieves the word error rate (WER) of 8.90% on the Wall Street Journal (WSJ) Nov'92 20K evaluation set when trained on the WSJ SI-284 training set.

##### Abstract (translated by Google)
在实时语音识别应用中，延迟是一个重要的问题。我们已经开发了一个字符级的增量式语音识别（ISR）系统，即使在讲话过程中也能迅速响应，在讲话过程中假设逐渐得到改善。该算法采用连接主义时态分类（CTC）端到端训练的语音单向递归神经网络（RNN）和基于RNN的特征级语言模型（LM）。 CTC训练的RNN的输出值是字符级概率，通过波束搜索解码处理。 RNN LM通过提供长期相关性信息来增强解码。我们提出了基于树的在线波束搜索和附加的深度修剪，使得系统能够以低延迟处理无限长的输入语音。这个系统不仅可以快速响应语音，还可以根据发音指定词汇外（OOV）词。在“华尔街日报”SI-284训练集上进行训练时，所提出的模型在“华尔街日报”（WSJ）Nov'92 20K评估集上实现了8.90％的字错误率（WER）

##### URL
[https://arxiv.org/abs/1601.06581](https://arxiv.org/abs/1601.06581)

##### PDF
[https://arxiv.org/pdf/1601.06581](https://arxiv.org/pdf/1601.06581)

