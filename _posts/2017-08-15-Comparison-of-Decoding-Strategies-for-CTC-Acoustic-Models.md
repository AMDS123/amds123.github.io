---
layout: post
title: "Comparison of Decoding Strategies for CTC Acoustic Models"
date: 2017-08-15 12:05:02
categories: arXiv_CL
tags: arXiv_CL GAN Speech_Recognition Classification Language_Model Recognition
author: Thomas Zenkel, Ramon Sanabria, Florian Metze, Jan Niehues, Matthias Sperber, Sebastian Stüker, Alex Waibel
mathjax: true
---

* content
{:toc}

##### Abstract
Connectionist Temporal Classification has recently attracted a lot of interest as it offers an elegant approach to building acoustic models (AMs) for speech recognition. The CTC loss function maps an input sequence of observable feature vectors to an output sequence of symbols. Output symbols are conditionally independent of each other under CTC loss, so a language model (LM) can be incorporated conveniently during decoding, retaining the traditional separation of acoustic and linguistic components in ASR. For fixed vocabularies, Weighted Finite State Transducers provide a strong baseline for efficient integration of CTC AMs with n-gram LMs. Character-based neural LMs provide a straight forward solution for open vocabulary speech recognition and all-neural models, and can be decoded with beam search. Finally, sequence-to-sequence models can be used to translate a sequence of individual sounds into a word string. We compare the performance of these three approaches, and analyze their error patterns, which provides insightful guidance for future research and development in this important area.

##### Abstract (translated by Google)
Connectionist Temporal Classification最近吸引了很多人的兴趣，因为它提供了一个优雅的方法来构建用于语音识别的声学模型（AM）。 CTC损失函数将可观察特征向量的输入序列映射到输出符号序列。输出符号在CTC丢失条件下是相互独立的，因此语言模型（LM）可以在解码过程中方便地使用，保留传统ASR中声学和语言组件的分离。对于固定词汇，加权有限状态转换器为CTC AM与n-gram LM的高效整合提供了强有力的基准。基于字符的神经LM为开放式词汇语音识别和全神经模型提供了直接的解决方案，并且可以利用波束搜索来解码。最后，序列到序列模型可以用来将一系列单独的声音转换成单词串。我们比较这三种方法的表现，并分析它们的错误模式，为这一重要领域的未来研究和发展提供有见地的指导。

##### URL
[https://arxiv.org/abs/1708.04469](https://arxiv.org/abs/1708.04469)

##### PDF
[https://arxiv.org/pdf/1708.04469](https://arxiv.org/pdf/1708.04469)

