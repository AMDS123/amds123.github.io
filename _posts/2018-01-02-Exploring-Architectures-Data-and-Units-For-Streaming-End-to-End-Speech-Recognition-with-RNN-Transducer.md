---
layout: post
title: "Exploring Architectures, Data and Units For Streaming End-to-End Speech Recognition with RNN-Transducer"
date: 2018-01-02 21:29:41
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition RNN Classification Language_Model Recognition
author: Kanishka Rao, Ha&#x15f;im Sak, Rohit Prabhavalkar
mathjax: true
---

* content
{:toc}

##### Abstract
We investigate training end-to-end speech recognition models with the recurrent neural network transducer (RNN-T): a streaming, all-neural, sequence-to-sequence architecture which jointly learns acoustic and language model components from transcribed acoustic data. We explore various model architectures and demonstrate how the model can be improved further if additional text or pronunciation data are available. The model consists of an `encoder', which is initialized from a connectionist temporal classification-based (CTC) acoustic model, and a `decoder' which is partially initialized from a recurrent neural network language model trained on text data alone. The entire neural network is trained with the RNN-T loss and directly outputs the recognized transcript as a sequence of graphemes, thus performing end-to-end speech recognition. We find that performance can be improved further through the use of sub-word units (`wordpieces') which capture longer context and significantly reduce substitution errors. The best RNN-T system, a twelve-layer LSTM encoder with a two-layer LSTM decoder trained with 30,000 wordpieces as output targets achieves a word error rate of 8.5\% on voice-search and 5.2\% on voice-dictation tasks and is comparable to a state-of-the-art baseline at 8.3\% on voice-search and 5.4\% voice-dictation.

##### Abstract (translated by Google)
我们使用递归神经网络换能器（RNN-T）研究训练端到端语音识别模型：流式全神经序列到序列结构，其共同学习来自转录声学数据的声学和语言模型组分。我们探索各种模型架构，并演示如果可以获得额外的文本或发音数据，模型可以进一步改进。该模型由一个“编码器”和一个“解码器”组成，该编码器是基于连接主义时间分类（CTC）声学模型初始化的，该解码器部分地由仅在文本数据上训练的递归神经网络语言模型初始化。整个神经网络用RNN-T损失进行训练，并直接输出被识别的成绩单作为一个字符序列，从而进行端到端的语音识别。我们发现，通过使用能够捕捉更长的上下文并显着减少替代错误的子字词单元（`wordpieces），可以进一步提高性能。最好的RNN-T系统是一个带有两层LSTM解码器的十二层LSTM编码器，其训练有三万个字节作为输出目标，对于语音搜索任务的字错误率为8.5％，语音听写任务的字错误率为5.2％与语音搜索的8.3％和语音听写的5.4％相当。

##### URL
[http://arxiv.org/abs/1801.00841](http://arxiv.org/abs/1801.00841)

##### PDF
[http://arxiv.org/pdf/1801.00841](http://arxiv.org/pdf/1801.00841)

