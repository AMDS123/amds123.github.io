---
layout: post
title: "An Online Attention-based Model for Speech Recognition"
date: 2019-04-25 09:13:17
categories: arXiv_CL
tags: arXiv_CL Attention Speech_Recognition Recognition
author: Ruchao Fan, Pan Zhou, Wei Chen, Jia Jia, Gang Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Attention-based end-to-end models such as Listen, Attend and Spell (LAS), simplify the whole pipeline of traditional automatic speech recognition (ASR) systems and become popular in the field of speech recognition. In previous work, researchers have shown that such architectures can acquire comparable results to state-of-the-art ASR systems, especially when using a bidirectional encoder and global soft attention (GSA) mechanism. However, bidirectional encoder and GSA are two obstacles for real-time speech recognition. In this work, we aim to stream LAS baseline by removing the above two obstacles. On the encoder side, we use a latency-controlled (LC) bidirectional structure to reduce the delay of forward computation. Meanwhile, an adaptive monotonic chunk-wise attention (AMoChA) mechanism is proposed to replace GSA for the calculation of attention weight distribution. Furthermore, we propose two methods to alleviate the huge performance degradation when combining LC and AMoChA. Finally, we successfully acquire an online LAS model, LC-AMoChA, which has only 3.5% relative performance reduction to LAS baseline on our internal Mandarin corpus.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.05247](http://arxiv.org/abs/1811.05247)

##### PDF
[http://arxiv.org/pdf/1811.05247](http://arxiv.org/pdf/1811.05247)

