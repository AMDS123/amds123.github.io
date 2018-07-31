---
layout: post
title: "Multi-Head Decoder for End-to-End Speech Recognition"
date: 2018-07-28 05:31:32
categories: arXiv_CL
tags: arXiv_CL Attention Speech_Recognition Recognition
author: Tomoki Hayashi, Shinji Watanabe, Tomoki Toda, Kazuya Takeda
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a new network architecture called multi-head decoder for end-to-end speech recognition as an extension of a multi-head attention model. In the multi-head attention model, multiple attentions are calculated, and then, they are integrated into a single attention. On the other hand, instead of the integration in the attention level, our proposed method uses multiple decoders for each attention and integrates their outputs to generate a final output. Furthermore, in order to make each head to capture the different modalities, different attention functions are used for each head, leading to the improvement of the recognition performance with an ensemble effect. To evaluate the effectiveness of our proposed method, we conduct an experimental evaluation using Corpus of Spontaneous Japanese. Experimental results demonstrate that our proposed method outperforms the conventional methods such as location-based and multi-head attention models, and that it can capture different speech/linguistic contexts within the attention-based encoder-decoder framework.

##### Abstract (translated by Google)
本文提出了一种新的网络架构，称为多头解码器，用于端到端语音识别，作为多头注意模型的扩展。在多头注意模型中，计算多个注意力，然后将它们集成到单个注意力中。另一方面，我们提出的方法不是集中注意力水平，而是针对每个注意力使用多个解码器并集成它们的输出以生成最终输出。此外，为了使每个头部捕获不同的模态，每个头部使用不同的注意功能，从而导致具有整体效果的识别性能的提高。为了评估我们提出的方法的有效性，我们使用自发日语语料库进行实验评估。实验结果表明，我们提出的方法优于传统方法，如基于位置和多头注意模型，并且它可以在基于注意力的编码器 - 解码器框架内捕获不同的语音/语言上下文。

##### URL
[http://arxiv.org/abs/1804.08050](http://arxiv.org/abs/1804.08050)

##### PDF
[http://arxiv.org/pdf/1804.08050](http://arxiv.org/pdf/1804.08050)

