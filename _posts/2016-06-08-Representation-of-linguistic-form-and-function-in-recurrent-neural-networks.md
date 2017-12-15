---
layout: post
title: "Representation of linguistic form and function in recurrent neural networks"
date: 2016-06-08 12:30:12
categories: arXiv_SD
tags: arXiv_SD Attention Embedding RNN Language_Model Prediction
author: Ákos Kádár, Grzegorz Chrupała, Afra Alishahi
mathjax: true
---

* content
{:toc}

##### Abstract
We present novel methods for analyzing the activation patterns of RNNs from a linguistic point of view and explore the types of linguistic structure they learn. As a case study, we use a multi-task gated recurrent network architecture consisting of two parallel pathways with shared word embeddings trained on predicting the representations of the visual scene corresponding to an input sentence, and predicting the next word in the same sentence. Based on our proposed method to estimate the amount of contribution of individual tokens in the input to the final prediction of the networks we show that the image prediction pathway: a) is sensitive to the information structure of the sentence b) pays selective attention to lexical categories and grammatical functions that carry semantic information c) learns to treat the same input token differently depending on its grammatical functions in the sentence. In contrast the language model is comparatively more sensitive to words with a syntactic function. Furthermore, we propose methods to ex- plore the function of individual hidden units in RNNs and show that the two pathways of the architecture in our case study contain specialized units tuned to patterns informative for the task, some of which can carry activations to later time steps to encode long-term dependencies.

##### Abstract (translated by Google)
从语言学的角度出发，分析RNN激活模式的新方法，探索其学习的语言结构类型。作为一个案例研究，我们使用一个多任务门控循环网络体系结构，由两条平行的路径组成，共享词嵌入训练用于预测与输入句子相对应的视觉场景的表示，并预测同一句子中的下一个词。基于我们提出的方法来估计单个代币在网络的最终预测输入中的贡献量，我们显示图像预测路径：a）对句子的信息结构敏感b）对词汇的选择性注意带有语义信息的类别和语法功能c）学习根据句子中的语法功能，不同地处理相同的输入标记。相比之下，语言模型相对于具有句法功能的单词更为敏感。此外，我们提出了探讨个体隐藏单位在RNNs中的作用的方法，并且表明在我们的案例研究中，这两个体系结构的路径包含专门的单位，这些单位被调整为用于任务的信息模式，其中一些可以在以后的时间编码长期依赖关系的步骤。

##### URL
[https://arxiv.org/abs/1602.08952](https://arxiv.org/abs/1602.08952)

##### PDF
[https://arxiv.org/pdf/1602.08952](https://arxiv.org/pdf/1602.08952)

