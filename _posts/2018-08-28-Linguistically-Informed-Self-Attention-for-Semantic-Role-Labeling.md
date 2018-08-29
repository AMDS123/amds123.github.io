---
layout: post
title: "Linguistically-Informed Self-Attention for Semantic Role Labeling"
date: 2018-08-28 00:03:58
categories: arXiv_CL
tags: arXiv_CL Attention Embedding Detection
author: Emma Strubell, Patrick Verga, Daniel Andor, David Weiss, Andrew McCallum
mathjax: true
---

* content
{:toc}

##### Abstract
Current state-of-the-art semantic role labeling (SRL) uses a deep neural network with no explicit linguistic features. However, prior work has shown that gold syntax trees can dramatically improve SRL decoding, suggesting the possibility of increased accuracy from explicit modeling of syntax. In this work, we present linguistically-informed self-attention (LISA): a neural network model that combines multi-head self-attention with multi-task learning across dependency parsing, part-of-speech tagging, predicate detection and SRL. Unlike previous models which require significant pre-processing to prepare linguistic features, LISA can incorporate syntax using merely raw tokens as input, encoding the sequence only once to simultaneously perform parsing, predicate detection and role labeling for all predicates. Syntax is incorporated by training one attention head to attend to syntactic parents for each token. Moreover, if a high-quality syntactic parse is already available, it can be beneficially injected at test time without re-training our SRL model. In experiments on CoNLL-2005 SRL, LISA achieves new state-of-the-art performance for a model using predicted predicates and standard word embeddings, attaining 2.5 F1 absolute higher than the previous state-of-the-art on newswire and more than 3.5 F1 on out-of-domain data, nearly 10% reduction in error. On ConLL-2012 English SRL we also show an improvement of more than 2.5 F1. LISA also out-performs the state-of-the-art with contextually-encoded (ELMo) word representations, by nearly 1.0 F1 on news and more than 2.0 F1 on out-of-domain text.

##### Abstract (translated by Google)
当前最先进的语义角色标记（SRL）使用深度神经网络而没有明确的语言特征。但是，之前的工作表明，黄金语法树可以显着改善SRL解码，这表明通过显式语法建模可以提高准确性。在这项工作中，我们提出了语言知情的自我关注（LISA）：一种神经网络模型，它将多头自我关注与多任务学习相结合，包括依赖解析，词性标注，谓词检测和SRL。与先前需要大量预处理来准备语言特征的模型不同，LISA可以仅使用原始令牌作为输入来合并语法，仅对序列编码一次以同时对所有谓词执行解析，谓词检测和角色标记。语法通过训练一个注意力头来参与每个令牌的句法父母。此外，如果已经有高质量的语法分析，则可以在测试时进行有益的注入，而无需重新训练我们的SRL模型。在CoNLL-2005 SRL的实验中，LISA使用预测谓词和标准字嵌入为模型实现了最新的最先进性能，比新闻专线上的先前技术水平高出2.5 F1绝对值3.5关于域外数据的F1，误差减少近10％。在ConLL-2012英语SRL上，我们也表现出超过2.5 F1的改进。 LISA还通过上下文编码（ELMo）单词表示超出了最新技术水平，在新闻上接近1.0 F1，在域外文本上超过2.0 F1。

##### URL
[http://arxiv.org/abs/1804.08199](http://arxiv.org/abs/1804.08199)

##### PDF
[http://arxiv.org/pdf/1804.08199](http://arxiv.org/pdf/1804.08199)

