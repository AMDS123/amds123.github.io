---
layout: post
title: "Constituency Parsing with a Self-Attentive Encoder"
date: 2018-05-02 23:21:12
categories: arXiv_CL
tags: arXiv_CL Attention RNN
author: Nikita Kitaev, Dan Klein
mathjax: true
---

* content
{:toc}

##### Abstract
We demonstrate that replacing an LSTM encoder with a self-attentive architecture can lead to improvements to a state-of-the-art discriminative constituency parser. The use of attention makes explicit the manner in which information is propagated between different locations in the sentence, which we use to both analyze our model and propose potential improvements. For example, we find that separating positional and content information in the encoder can lead to improved parsing accuracy. Additionally, we evaluate different approaches for lexical representation. Our parser achieves new state-of-the-art results for single models trained on the Penn Treebank: 93.55 F1 without the use of any external data, and 95.13 F1 when using pre-trained word representations. Our parser also outperforms the previous best-published accuracy figures on 8 of the 9 languages in the SPMRL dataset.

##### Abstract (translated by Google)
我们证明，用一种自我关注的体系结构取代LSTM编码器可以改进最先进的区分性选区解析器。注意的使用明确了信息在句子中不同位置之间传播的方式，我们用它来分析我们的模型并提出潜在的改进。例如，我们发现在编码器中分离位置和内容信息可以提高分析的准确性。此外，我们评估不同的词汇表达方法。我们的解析器为Penn Treebank上训练的单一模型获得了最新的最新结果：93.55 F1不使用任何外部数据，95.13 F1使用预先训练的词语表示。我们的解析器还胜过了SPMRL数据集中9种语言中的8种语言的以前发布的最佳准确度数据。

##### URL
[http://arxiv.org/abs/1805.01052](http://arxiv.org/abs/1805.01052)

##### PDF
[http://arxiv.org/pdf/1805.01052](http://arxiv.org/pdf/1805.01052)

