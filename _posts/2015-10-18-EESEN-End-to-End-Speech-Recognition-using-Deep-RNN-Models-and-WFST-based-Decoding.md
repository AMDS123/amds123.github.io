---
layout: post
title: "EESEN: End-to-End Speech Recognition using Deep RNN Models and WFST-based Decoding"
date: 2015-10-18 20:35:52
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition RNN Classification Language_Model Recognition
author: Yajie Miao, Mohammad Gowayyed, Florian Metze
mathjax: true
---

* content
{:toc}

##### Abstract
The performance of automatic speech recognition (ASR) has improved tremendously due to the application of deep neural networks (DNNs). Despite this progress, building a new ASR system remains a challenging task, requiring various resources, multiple training stages and significant expertise. This paper presents our Eesen framework which drastically simplifies the existing pipeline to build state-of-the-art ASR systems. Acoustic modeling in Eesen involves learning a single recurrent neural network (RNN) predicting context-independent targets (phonemes or characters). To remove the need for pre-generated frame labels, we adopt the connectionist temporal classification (CTC) objective function to infer the alignments between speech and label sequences. A distinctive feature of Eesen is a generalized decoding approach based on weighted finite-state transducers (WFSTs), which enables the efficient incorporation of lexicons and language models into CTC decoding. Experiments show that compared with the standard hybrid DNN systems, Eesen achieves comparable word error rates (WERs), while at the same time speeding up decoding significantly.

##### Abstract (translated by Google)
由于深度神经网络（DNN）的应用，自动语音识别（ASR）的性能得到了极大的提高。尽管取得了这些进展，但建立一个新的ASR系统仍然是一项艰巨的任务，需要各种资源，多个培训阶段和重要的专业知本文介绍了我们的Eesen框架，大大简化了现有的管道，以建立最先进的ASR系统。 Eesen中的声学建模包括学习一个预测独立于上下文的目标（音素或字符）的单一递归神经网络（RNN）。为了消除对预先生成的帧标签的需求，我们采用连接主义时间分类（CTC）目标函数来推断语音和标签序列之间的对齐。 Eesen的一个显着特点是基于加权有限状态转换器（WFST）的广义解码方法，它能够有效地将词典和语言模型合并到CTC解码中。实验表明，与标准的混合DNN系统相比，Eesen达到了可比的字错误率（WER），同时显着加速了解码。

##### URL
[https://arxiv.org/abs/1507.08240](https://arxiv.org/abs/1507.08240)

##### PDF
[https://arxiv.org/pdf/1507.08240](https://arxiv.org/pdf/1507.08240)

