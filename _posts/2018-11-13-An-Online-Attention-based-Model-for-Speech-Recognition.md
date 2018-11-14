---
layout: post
title: "An Online Attention-based Model for Speech Recognition"
date: 2018-11-13 12:23:37
categories: arXiv_CL
tags: arXiv_CL Attention Speech_Recognition RNN Language_Model Recognition
author: Ruchao Fan, Pan Zhou, Wei Chen, Jia Jia, Gang Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Attention-based end-to-end (E2E) speech recognition models such as Listen, Attend, and Spell (LAS) can achieve better results than traditional automatic speech recognition (ASR) hybrid models on LVCSR tasks. LAS combines acoustic, pronunciation and language model components of a traditional ASR system into a single neural network. However, such architectures are hard to be used for streaming speech recognition for its bidirectional listener architecture and attention mechanism. In this work, we propose to use latency-controlled bidirectional long short-term memory (LC- BLSTM) listener to reduce the delay of forward computing of listener. On the attention side, we propose an adaptive monotonic chunk-wise attention (AMoChA) to make LAS online. We explore how each part performs when it is used alone and obtain comparable or better results than LAS baseline. By combining the above two methods, we successfully stream LAS baseline with only 3.5% relative degradation of character error rate (CER) on our Mandarin corpus. We believe that our methods can also have the same effect on other languages.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.05247](https://arxiv.org/abs/1811.05247)

##### PDF
[https://arxiv.org/pdf/1811.05247](https://arxiv.org/pdf/1811.05247)

