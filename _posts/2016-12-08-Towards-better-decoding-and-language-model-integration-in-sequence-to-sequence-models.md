---
layout: post
title: "Towards better decoding and language model integration in sequence to sequence models"
date: 2016-12-08 15:23:44
categories: arXiv_CL
tags: arXiv_CL Attention Speech_Recognition Language_Model Prediction Recognition
author: Jan Chorowski, Navdeep Jaitly
mathjax: true
---

* content
{:toc}

##### Abstract
The recently proposed Sequence-to-Sequence (seq2seq) framework advocates replacing complex data processing pipelines, such as an entire automatic speech recognition system, with a single neural network trained in an end-to-end fashion. In this contribution, we analyse an attention-based seq2seq speech recognition system that directly transcribes recordings into characters. We observe two shortcomings: overconfidence in its predictions and a tendency to produce incomplete transcriptions when language models are used. We propose practical solutions to both problems achieving competitive speaker independent word error rates on the Wall Street Journal dataset: without separate language models we reach 10.6% WER, while together with a trigram language model, we reach 6.7% WER.

##### Abstract (translated by Google)
最近提出的序列到序列（sequence-to-sequence，seq2seq）框架主张用单端神经网络来代替复杂的数据处理流水线，如整个自动语音识别系统。在这个贡献中，我们分析了一个基于注意力的seq2seq语音识别系统，可以直接将录音转换成字符。我们观察到两个缺点：过度自信的预测和使用语言模型时产生不完整的转录的倾向。我们针对在华尔街日报数据集中获得竞争性说话者独立词汇错误率的两个问题提出了实用的解决方案：没有单独的语言模型，我们达到了10.6％的WER，而与三字母语言模型一起，我们达到了6.7％的WER。

##### URL
[https://arxiv.org/abs/1612.02695](https://arxiv.org/abs/1612.02695)

##### PDF
[https://arxiv.org/pdf/1612.02695](https://arxiv.org/pdf/1612.02695)

