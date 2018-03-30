---
layout: post
title: "Multi-Modal Data Augmentation for End-to-end ASR"
date: 2018-03-27 20:12:39
categories: arXiv_CL
tags: arXiv_CL Attention Speech_Recognition Recognition
author: Adithya Renduchintala, Shuoyang Ding, Matthew Wiesner, Shinji Watanabe
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new end-to-end architecture for automatic speech recognition (ASR) that can be trained using \emph{symbolic} input in addition to the traditional acoustic input. This architecture utilizes two separate encoders: one for acoustic input and another for symbolic input, both sharing the attention and decoder parameters. We call this architecture a multi-modal data augmentation network (MMDA), as it can support multi-modal (acoustic and symbolic) input. The MMDA architecture attempts to eliminate the need for an external LM, by enabling seamless mixing of large text datasets with significantly smaller transcribed speech corpora during training. We study different ways of transforming large text corpora into a symbolic form suitable for training our MMDA network. Our best MMDA setup obtains small improvements on CER and achieves 8-10\% relative WER improvement on the WSJ data set.

##### Abstract (translated by Google)
我们提出了一种新的自动语音识别（ASR）端到端架构，除了传统的声学输入外，还可以使用\ emph {symbolic}输入进行训练。该架构使用两个独立的编码器：一个用于声音输入，另一个用于符号输入，两者共享注意力和解码器参数。我们称这种架构为多模式数据增强网络（MMDA），因为它可以支持多模式（声音和符号）输入。 MMDA体系结构试图通过在训练过程中将大型文本数据集与小得多的转录语音库无缝混合，来消除对外部LM的需求。我们研究将大型文本语料库转换为适合培训MMDA网络的符号形式的不同方式。我们最好的MMDA设置在CER方面取得了小幅进展，并实现了WSJ数据集相对WER改进8-10％的相对改进。

##### URL
[https://arxiv.org/abs/1803.10299](https://arxiv.org/abs/1803.10299)

##### PDF
[https://arxiv.org/pdf/1803.10299](https://arxiv.org/pdf/1803.10299)

