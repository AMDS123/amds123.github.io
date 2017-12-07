---
layout: post
title: "An analysis of incorporating an external language model into a sequence-to-sequence model"
date: 2017-12-06 01:30:54
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Recognition
author: Anjuli Kannan, Yonghui Wu, Patrick Nguyen, Tara N. Sainath, Zhifeng Chen, Rohit Prabhavalkar
mathjax: true
---

* content
{:toc}

##### Abstract
Attention-based sequence-to-sequence models for automatic speech recognition jointly train an acoustic model, language model, and alignment mechanism. Thus, the language model component is only trained on transcribed audio-text pairs. This leads to the use of shallow fusion with an external language model at inference time. Shallow fusion refers to log-linear interpolation with a separately trained language model at each step of the beam search. In this work, we investigate the behavior of shallow fusion across a range of conditions: different types of language models, different decoding units, and different tasks. On Google Voice Search, we demonstrate that the use of shallow fusion with a neural LM with wordpieces yields a 9.1% relative word error rate reduction (WERR) over our competitive attention-based sequence-to-sequence model, obviating the need for second-pass rescoring.

##### Abstract (translated by Google)
用于自动语音识别的基于注意的序列 - 序列模型共同训练声学模型，语言模型和对齐机制。因此，语言模型组件仅在转录的音频文本对上训练。这导致在推理时使用与外部语言模型的浅融合。浅融合指的是在波束搜索的每个步骤中利用单独训练的语言模型的对数线性插值。在这项工作中，我们调查了一系列条件下浅层融合的行为：不同类型的语言模型，不同的解码单元和不同的任务。在谷歌语音搜索，我们表明，使用与神经LM与字的浅融合产生相对于我们竞争的注重序列到序列模型9.1％的相对字错误率减少（WERR），无需二次开发，通过rescoring。

##### URL
[http://arxiv.org/abs/1712.01996](http://arxiv.org/abs/1712.01996)

##### PDF
[http://arxiv.org/pdf/1712.01996](http://arxiv.org/pdf/1712.01996)

