---
layout: post
title: "Multi-Modal Data Augmentation for End-to-End ASR"
date: 2018-06-18 05:53:10
categories: arXiv_CL
tags: arXiv_CL Attention Speech_Recognition Language_Model Recognition
author: Adithya Renduchintala, Shuoyang Ding, Matthew Wiesner, Shinji Watanabe
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new end-to-end architecture for automatic speech recognition (ASR) that can be trained using \emph{symbolic} input in addition to the traditional acoustic input. This architecture utilizes two separate encoders: one for acoustic input and another for symbolic input, both sharing the attention and decoder parameters. We call this architecture a multi-modal data augmentation network (MMDA), as it can support multi-modal (acoustic and symbolic) input and enables seamless mixing of large text datasets with significantly smaller transcribed speech corpora during training. We study different ways of transforming large text corpora into a symbolic form suitable for training our MMDA network. Our best MMDA setup obtains small improvements on character error rate (CER), and as much as 7-10\% relative word error rate (WER) improvement over a baseline both with and without an external language model.

##### Abstract (translated by Google)
我们提出了一种新的自动语音识别（ASR）端到端架构，除了传统的声学输入外，还可以使用\ emph {symbolic}输入进行训练。该架构使用两个独立的编码器：一个用于声音输入，另一个用于符号输入，两者共享注意力和解码器参数。我们称这种体系结构为多模式数据增强网络（MMDA），因为它可以支持多模式（声学和符号）输入，并且可以在训练期间将大型文本数据集无缝混合到转录的语音语料库中。我们研究将大型文本语料库转换为适合培训MMDA网络的符号形式的不同方式。我们最好的MMDA设置在字符错误率（CER）方面获得小的改进，并且在有或没有外部语言模型的情况下，相对于基线的相对字错误率（WER）提高多达7-10％。

##### URL
[http://arxiv.org/abs/1803.10299](http://arxiv.org/abs/1803.10299)

##### PDF
[http://arxiv.org/pdf/1803.10299](http://arxiv.org/pdf/1803.10299)

