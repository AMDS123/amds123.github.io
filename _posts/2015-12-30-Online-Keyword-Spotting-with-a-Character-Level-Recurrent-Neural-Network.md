---
layout: post
title: "Online Keyword Spotting with a Character-Level Recurrent Neural Network"
date: 2015-12-30 10:32:12
categories: arXiv_CL
tags: arXiv_CL Segmentation RNN Classification Detection
author: Kyuyeon Hwang, Minjae Lee, Wonyong Sung
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a context-aware keyword spotting model employing a character-level recurrent neural network (RNN) for spoken term detection in continuous speech. The RNN is end-to-end trained with connectionist temporal classification (CTC) to generate the probabilities of character and word-boundary labels. There is no need for the phonetic transcription, senone modeling, or system dictionary in training and testing. Also, keywords can easily be added and modified by editing the text based keyword list without retraining the RNN. Moreover, the unidirectional RNN processes an infinitely long input audio streams without pre-segmentation and keywords are detected with low-latency before the utterance is finished. Experimental results show that the proposed keyword spotter significantly outperforms the deep neural network (DNN) and hidden Markov model (HMM) based keyword-filler model even with less computations.

##### Abstract (translated by Google)
在本文中，我们提出了一个上下文感知的关键字点击模型，采用字符级递归神经网络（RNN）进行连续语音的口头检测。 RNN是用连接主义时间分类（CTC）进行端对端训练以产生字符和文字边界标签的概率。在训练和测试中，不需要拼音，句子建模或系统字典。此外，通过编辑基于文本的关键字列表，可以轻松地添加和修改关键字，而无需重新训练RNN。此外，单向RNN在无预分割的情况下处理无限长的输入音频流，并且在发声完成之前以低等待时间检测关键字。实验结果表明，即使计算量较少，所提出的关键字查找器也显着优于深度神经网络（DNN）和基于隐马尔可夫模型（HMM）的关键字填充模型。

##### URL
[https://arxiv.org/abs/1512.08903](https://arxiv.org/abs/1512.08903)

##### PDF
[https://arxiv.org/pdf/1512.08903](https://arxiv.org/pdf/1512.08903)

