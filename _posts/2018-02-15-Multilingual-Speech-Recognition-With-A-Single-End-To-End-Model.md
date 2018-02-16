---
layout: post
title: "Multilingual Speech Recognition With A Single End-To-End Model"
date: 2018-02-15 08:59:27
categories: arXiv_AI
tags: arXiv_AI Speech_Recognition Language_Model Recognition
author: Shubham Toshniwal, Tara N. Sainath, Ron J. Weiss, Bo Li, Pedro Moreno, Eugene Weinstein, Kanishka Rao
mathjax: true
---

* content
{:toc}

##### Abstract
Training a conventional automatic speech recognition (ASR) system to support multiple languages is challenging because the sub-word unit, lexicon and word inventories are typically language specific. In contrast, sequence-to-sequence models are well suited for multilingual ASR because they encapsulate an acoustic, pronunciation and language model jointly in a single network. In this work we present a single sequence-to-sequence ASR model trained on 9 different Indian languages, which have very little overlap in their scripts. Specifically, we take a union of language-specific grapheme sets and train a grapheme-based sequence-to-sequence model jointly on data from all languages. We find that this model, which is not explicitly given any information about language identity, improves recognition performance by 21% relative compared to analogous sequence-to-sequence models trained on each language individually. By modifying the model to accept a language identifier as an additional input feature, we further improve performance by an additional 7% relative and eliminate confusion between different languages.

##### Abstract (translated by Google)
训练传统的自动语音识别（ASR）系统以支持多种语言是具有挑战性的，因为子词单元，词典和词语清单通常是特定于语言的。相比之下，序列到序列模型非常适合多语言ASR，因为它们在单个网络中共同封装了声学，发音和语言模型。在这项工作中，我们展示了一个单独的序列到序列的ASR模型，它们使用9种不同的印度语言进行训练，这些语言在脚本中几乎没有重叠。具体而言，我们采用语言特定的字形集合并联合训练基于字形的序列到序列模型，并结合所有语言的数据。我们发现这个模型没有明确给出有关语言身份的任何信息，与单独训练每个语言的类似序列 - 序列模型相比，识别性能提高了21％。通过修改模型以接受语言标识符作为额外的输入功能，我们将性能进一步提高7％，并消除不同语言之间的混淆。

##### URL
[http://arxiv.org/abs/1711.01694](http://arxiv.org/abs/1711.01694)

##### PDF
[http://arxiv.org/pdf/1711.01694](http://arxiv.org/pdf/1711.01694)

