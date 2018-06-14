---
layout: post
title: "Multilingual End-to-End Speech Recognition with A Single Transformer on Low-Resource Languages"
date: 2018-06-12 05:13:04
categories: arXiv_CL
tags: arXiv_CL Attention Speech_Recognition RNN Language_Model Recognition
author: Shiyu Zhou, Shuang Xu, Bo Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Sequence-to-sequence attention-based models integrate an acoustic, pronunciation and language model into a single neural network, which make them very suitable for multilingual automatic speech recognition (ASR). In this paper, we are concerned with multilingual end-to-end speech recognition on low-resource languages by a single Transformer, one of sequence-to-sequence attention-based models. Sub-words are employed as the multilingual modeling unit without using any pronunciation lexicon. First, we show that a single multilingual ASR Transformer performs well on low-resource languages despite of some language confusion. We then look at incorporating language-specific information into the model by inserting the language symbol at the beginning or at the end of the original sub-words sequence under the condition of language information being known during training. Experiments on CALLHOME datasets demonstrate that the multilingual ASR Transformer with the language symbol at the end performs better and can obtain relatively 10.5\% average word error rate (WER) reduction compared to SHL-MLSTM with residual learning. We go on to show that, assuming the language information being known during training and testing, about relatively 12.4\% average WER reduction can be observed compared to SHL-MLSTM with residual learning through giving the language symbol as the sentence start token.

##### Abstract (translated by Google)
序列到序列注意的模型将声学，发音和语言模型集成到单个神经网络中，这使得它们非常适合多语言自动语音识别（ASR）。在本文中，我们关注通过单个变压器（一种序列到序列注意模型）在低资源语言上进行多语言端对端语音识别。子词被用作多语言建模单元而不使用任何发音词典。首先，我们展示了单个多语言ASR变压器在低资源语言下表现良好，尽管语言混乱。然后，我们考虑在语言信息在训练期间已知的条件下，将语言符号插入原始子字词序列的开始或结尾处，将语言特定的信息并入模型中。在CALLHOME数据集上的实验表明，与具有残差学习的SHL-MLSTM相比，具有语言符号的多语言ASR变换器表现更好，并且可以获得相对10.5％的平均字错误率（WER）降低。我们继续证明，假设语言信息在训练和测试期间是已知的，通过给出语言符号作为句子开始标记，与通过剩余学习的SHL-MLSTM相比，可观察到相对12.4％的平均WER减少。

##### URL
[https://arxiv.org/abs/1806.05059](https://arxiv.org/abs/1806.05059)

##### PDF
[https://arxiv.org/pdf/1806.05059](https://arxiv.org/pdf/1806.05059)

