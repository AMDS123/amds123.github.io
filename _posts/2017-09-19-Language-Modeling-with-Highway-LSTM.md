---
layout: post
title: "Language Modeling with Highway LSTM"
date: 2017-09-19 14:04:15
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition RNN Language_Model Recognition
author: Gakuto Kurata, Bhuvana Ramabhadran, George Saon, Abhinav Sethy
mathjax: true
---

* content
{:toc}

##### Abstract
Language models (LMs) based on Long Short Term Memory (LSTM) have shown good gains in many automatic speech recognition tasks. In this paper, we extend an LSTM by adding highway networks inside an LSTM and use the resulting Highway LSTM (HW-LSTM) model for language modeling. The added highway networks increase the depth in the time dimension. Since a typical LSTM has two internal states, a memory cell and a hidden state, we compare various types of HW-LSTM by adding highway networks onto the memory cell and/or the hidden state. Experimental results on English broadcast news and conversational telephone speech recognition show that the proposed HW-LSTM LM improves speech recognition accuracy on top of a strong LSTM LM baseline. We report 5.1% and 9.9% on the Switchboard and CallHome subsets of the Hub5 2000 evaluation, which reaches the best performance numbers reported on these tasks to date.

##### Abstract (translated by Google)
基于长期短期记忆（LSTM）的语言模型（LM）在许多自动语音识别任务中已经表现出很好的收益。在本文中，我们通过在LSTM中添加公路网络来扩展LSTM，并使用由此产生的Highway LSTM（HW-LSTM）模型进行语言建模。增加的高速公路网络增加了时间维度的深度。由于典型的LSTM具有两种内部状态，即存储单元和隐藏状态，我们通过将高速公路网络添加到存储单元和/或隐藏状态来比较各种类型的HW-LSTM。在英语广播新闻和会话电话语音识别上的实验结果表明，所提出的HW-LSTM LM在强LSTM LM基线之上提高了语音识别精度。我们在Hub5 2000评估版的Switchboard和CallHome子集上报告了5.1％和9.9％，达到了迄今为​​止报告的最佳性能数据。

##### URL
[https://arxiv.org/abs/1709.06436](https://arxiv.org/abs/1709.06436)

##### PDF
[https://arxiv.org/pdf/1709.06436](https://arxiv.org/pdf/1709.06436)

