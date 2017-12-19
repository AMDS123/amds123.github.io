---
layout: post
title: "Listen, Attend and Spell"
date: 2015-08-20 00:38:43
categories: arXiv_CL
tags: arXiv_CL Attention Language_Model
author: William Chan, Navdeep Jaitly, Quoc V. Le, Oriol Vinyals
mathjax: true
---

* content
{:toc}

##### Abstract
We present Listen, Attend and Spell (LAS), a neural network that learns to transcribe speech utterances to characters. Unlike traditional DNN-HMM models, this model learns all the components of a speech recognizer jointly. Our system has two components: a listener and a speller. The listener is a pyramidal recurrent network encoder that accepts filter bank spectra as inputs. The speller is an attention-based recurrent network decoder that emits characters as outputs. The network produces character sequences without making any independence assumptions between the characters. This is the key improvement of LAS over previous end-to-end CTC models. On a subset of the Google voice search task, LAS achieves a word error rate (WER) of 14.1% without a dictionary or a language model, and 10.3% with language model rescoring over the top 32 beams. By comparison, the state-of-the-art CLDNN-HMM model achieves a WER of 8.0%.

##### Abstract (translated by Google)
我们提出Listen，Attend和Spell（LAS），一个神经网络，学习将语音话语转化为人物。与传统的DNN-HMM模型不同，该模型共同学习语音识别器的所有组件。我们的系统有两个组件：一个监听器和一个拼写器。收听者是一个金字塔式经常性网络编码器，它接受滤波器组频谱作为输入。拼写器是一个基于注意的循环网络解码器，可以输出字符。网络产生字符序列而不会在字符之间做出任何独立的假设。这是LAS比之前的端到端CTC模型的关键改进。在Google语音搜索任务的一个子集中，LAS在没有字典或语言模型的情况下实现了14.1％的字错误率（WER），并且在顶部32个波束上重新计算了10.3％的语言模型。相比之下，最先进的CLDNN-HMM模型达到了8.0％的WER。

##### URL
[https://arxiv.org/abs/1508.01211](https://arxiv.org/abs/1508.01211)

##### PDF
[https://arxiv.org/pdf/1508.01211](https://arxiv.org/pdf/1508.01211)

