---
layout: post
title: "Learning from Past Mistakes: Improving Automatic Speech Recognition Output via Noisy-Clean Phrase Context Modeling"
date: 2018-02-07 19:30:17
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Optimization Language_Model Recognition
author: Prashanth Gurunath Shivakumar, Haoqi Li, Kevin Knight, Panayiotis Georgiou
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic speech recognition (ASR) systems lack joint optimization during decoding over the acoustic, lexical and language models; for instance the ASR will often prune words due to acoustics using short-term context, prior to rescoring with long-term context. In this work we model the automated speech transcription process as a noisy transformation channel and propose an error correction system that can learn from the aggregate errors of all the independent modules constituting the ASR. The proposed system can exploit long-term context using a neural network language model and can better choose between existing ASR output possibilities as well as re-introduce previously pruned and unseen (out-of-vocabulary) phrases. The system provides significant corrections under poorly performing ASR conditions without degrading any accurate transcriptions. The proposed system can thus be independently optimized and post-process the output of even a highly optimized ASR. We show that the system consistently provides improvements over the baseline ASR. We also show that it performs better when used on out-of-domain and mismatched test data and under high-error ASR conditions. Finally, an extensive analysis of the type of errors corrected by our system is presented.

##### Abstract (translated by Google)
自动语音识别（ASR）系统在声学，词汇和语言模型解码期间缺乏联合优化;例如，ASR通常会在长期上下文重新编码之前使用短期上下文来修剪由于声学造成的词汇。在这项工作中，我们将自动语音转录过程建模为噪声转换通道，并提出一个可以从构成ASR的所有独立模块的聚合错误中学习的错误校正系统。所提出的系统可以利用神经网络语言模型利用长期上下文，并且可以更好地选择现有的ASR输出可能性以及重新引入之前修剪的和看不见的（词汇表外的）短语。该系统在性能较差的ASR条件下提供显着的校正，而不降低任何准确的转录。所提出的系统因此可以被独立优化，并且后处理即使是高度优化的ASR的输出。我们显示系统始终提供了基准ASR的改进。我们还表明，当在域外和不匹配的测试数据以及高错误的ASR条件下使用时性能会更好。最后，对我们的系统纠正的错误类型进行了广泛的分析。

##### URL
[http://arxiv.org/abs/1802.02607](http://arxiv.org/abs/1802.02607)

##### PDF
[http://arxiv.org/pdf/1802.02607](http://arxiv.org/pdf/1802.02607)

