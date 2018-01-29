---
layout: post
title: "A Multilayer Convolutional Encoder-Decoder Neural Network for Grammatical Error Correction"
date: 2018-01-26 14:45:24
categories: arXiv_CL
tags: arXiv_CL Attention Embedding CNN RNN Language_Model
author: Shamil Chollampatt, Hwee Tou Ng
mathjax: true
---

* content
{:toc}

##### Abstract
We improve automatic correction of grammatical, orthographic, and collocation errors in text using a multilayer convolutional encoder-decoder neural network. The network is initialized with embeddings that make use of character N-gram information to better suit this task. When evaluated on common benchmark test data sets (CoNLL-2014 and JFLEG), our model substantially outperforms all prior neural approaches on this task as well as strong statistical machine translation-based systems with neural and task-specific features trained on the same data. Our analysis shows the superiority of convolutional neural networks over recurrent neural networks such as long short-term memory (LSTM) networks in capturing the local context via attention, and thereby improving the coverage in correcting grammatical errors. By ensembling multiple models, and incorporating an N-gram language model and edit features via rescoring, our novel method becomes the first neural approach to outperform the current state-of-the-art statistical machine translation-based approach, both in terms of grammaticality and fluency.

##### Abstract (translated by Google)
我们使用多层卷积编码器 - 解码器神经网络来改进文本中的语法，拼写和搭配错误的自动校正。网络使用字符N-gram信息嵌入进行初始化，以更好地适应此任务。当对通用的基准测试数据集（CoNLL-2014和JFLEG）进行评估时，我们的模型远远优于此前的所有神经方法，以及强大的基于统计机器翻译的系统，并在相同数据上训练了神经和特定任务特征。我们的分析表明，卷积神经网络优于回归神经网络，如长时间短记忆（LSTM）网络，通过注意捕捉本地情境，从而提高了纠正语法错误的覆盖率。通过整合多个模型，并结合N-gram语言模型和通过重新编辑来编辑特征，我们的新方法成为超越当前最新的基于统计机器翻译的方法的第一种神经方法，无论是在语法上流畅。

##### URL
[https://arxiv.org/abs/1801.08831](https://arxiv.org/abs/1801.08831)

##### PDF
[https://arxiv.org/pdf/1801.08831](https://arxiv.org/pdf/1801.08831)

