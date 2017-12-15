---
layout: post
title: "Learning Natural Language Inference using Bidirectional LSTM model and Inner-Attention"
date: 2016-05-30 02:47:35
categories: arXiv_CL
tags: arXiv_CL Attention Inference RNN
author: Yang Liu, Chengjie Sun, Lei Lin, Xiaolong Wang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we proposed a sentence encoding-based model for recognizing text entailment. In our approach, the encoding of sentence is a two-stage process. Firstly, average pooling was used over word-level bidirectional LSTM (biLSTM) to generate a first-stage sentence representation. Secondly, attention mechanism was employed to replace average pooling on the same sentence for better representations. Instead of using target sentence to attend words in source sentence, we utilized the sentence's first-stage representation to attend words appeared in itself, which is called "Inner-Attention" in our paper . Experiments conducted on Stanford Natural Language Inference (SNLI) Corpus has proved the effectiveness of "Inner-Attention" mechanism. With less number of parameters, our model outperformed the existing best sentence encoding-based approach by a large margin.

##### Abstract (translated by Google)
在本文中，我们提出了一个基于句子编码的文本识别模型。在我们的方法中，句子的编码是一个两阶段的过程。首先，平均汇集被用于字级双向LSTM（biLSTM）以产生第一阶段句子表示。其次，采用注意机制来取代同一句话的平均汇集，以便更好地表达。我们用源句中的目标句来代替句子中的单词，而是利用句子的第一阶段表征来出现本身出现的单词，在本文中被称为“内在注意”。在斯坦福自然语言推理（SNLI）语料库上进行的实验证明了“内在注意”机制的有效性。由于参数数量较少，我们的模型大大优于现有的基于最佳句子编码的方法。

##### URL
[https://arxiv.org/abs/1605.09090](https://arxiv.org/abs/1605.09090)

##### PDF
[https://arxiv.org/pdf/1605.09090](https://arxiv.org/pdf/1605.09090)

