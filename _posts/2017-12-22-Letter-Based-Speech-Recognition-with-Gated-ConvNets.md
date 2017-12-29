---
layout: post
title: "Letter-Based Speech Recognition with Gated ConvNets"
date: 2017-12-22 17:42:15
categories: arXiv_AI
tags: arXiv_AI Speech_Recognition Inference Language_Model Recognition
author: Vitaliy Liptchinsky, Gabriel Synnaeve, Ronan Collobert
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we introduce a new speech recognition system, leveraging a simple letter-based ConvNet acoustic model. The acoustic model requires -- only audio transcription for training -- no alignment annotations, nor any forced alignment step is needed. At inference, our decoder takes only a word list and a language model, and is fed with letter scores from the -- acoustic model -- no phonetic word lexicon is needed. Key ingredients for the acoustic model are Gated Linear Units and high dropout. We show near state-of-the-art results in word error rate on the LibriSpeech corpus using log-mel filterbanks, both on the "clean" and "other" configurations.

##### Abstract (translated by Google)
在本文中，我们引入一个新的语音识别系统，利用一个简单的基于字母的ConvNet声学模型。声学模型只需要 - 用于训练的音频转录 - 不需要对准注释，也不需要任何强制对准步骤。在推理中，我们的解码器只需要一个单词列表和一个语言模型，并且用从声学模型得到的字母分数来填充 - 不需要语音词汇词典。声学模型的关键要素是门控线性单位和高压差。在“干净”和“其他”配置中，我们使用log-mel filterbanks在LibriSpeech语料库上显示近乎最新的结果。

##### URL
[http://arxiv.org/abs/1712.09444](http://arxiv.org/abs/1712.09444)

##### PDF
[http://arxiv.org/pdf/1712.09444](http://arxiv.org/pdf/1712.09444)

