---
layout: post
title: "Character-Level Language Modeling with Hierarchical Recurrent Neural Networks"
date: 2017-02-02 13:49:41
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition RNN Language_Model Recognition
author: Kyuyeon Hwang, Wonyong Sung
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent neural network (RNN) based character-level language models (CLMs) are extremely useful for modeling out-of-vocabulary words by nature. However, their performance is generally much worse than the word-level language models (WLMs), since CLMs need to consider longer history of tokens to properly predict the next one. We address this problem by proposing hierarchical RNN architectures, which consist of multiple modules with different timescales. Despite the multi-timescale structures, the input and output layers operate with the character-level clock, which allows the existing RNN CLM training approaches to be directly applicable without any modifications. Our CLM models show better perplexity than Kneser-Ney (KN) 5-gram WLMs on the One Billion Word Benchmark with only 2% of parameters. Also, we present real-time character-level end-to-end speech recognition examples on the Wall Street Journal (WSJ) corpus, where replacing traditional mono-clock RNN CLMs with the proposed models results in better recognition accuracies even though the number of parameters are reduced to 30%.

##### Abstract (translated by Google)
基于递归神经网络（RNN）的字符级语言模型（CLM）非常适用于本质上对词典外单词进行建模。但是，由于CLM需要考虑更长的令牌历史来正确预测下一个令牌，所以它们的性能通常比字级语言模型（WLM）差得多。我们通过提出分层RNN体系结构来解决这个问题，该体系结构由多个不同时间尺度的模块组成。尽管多时间尺度的结构，输入和输出层与字符级时钟一起工作，这使得现有的RNN CLM训练方法可以直接适用而不需要任何修改。我们的CLM模型显示比十亿字基准上Kneser-Ney（KN）5克WLMs更好的困惑，只有2％的参数。另外，我们在华尔街日报（WSJ）语料库上提出了实时的字符级端到端语音识别实例，其中用所提出的模型取代传统的单时钟RNN CLMs导致更好的识别精度，即使参数降低到30％。

##### URL
[https://arxiv.org/abs/1609.03777](https://arxiv.org/abs/1609.03777)

##### PDF
[https://arxiv.org/pdf/1609.03777](https://arxiv.org/pdf/1609.03777)

