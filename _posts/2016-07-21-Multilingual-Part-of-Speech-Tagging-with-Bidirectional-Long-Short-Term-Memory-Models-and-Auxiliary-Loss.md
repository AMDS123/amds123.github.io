---
layout: post
title: "Multilingual Part-of-Speech Tagging with Bidirectional Long Short-Term Memory Models and Auxiliary Loss"
date: 2016-07-21 08:17:43
categories: arXiv_SD
tags: arXiv_SD Embedding RNN
author: Barbara Plank, Anders Søgaard, Yoav Goldberg
mathjax: true
---

* content
{:toc}

##### Abstract
Bidirectional long short-term memory (bi-LSTM) networks have recently proven successful for various NLP sequence modeling tasks, but little is known about their reliance to input representations, target languages, data set size, and label noise. We address these issues and evaluate bi-LSTMs with word, character, and unicode byte embeddings for POS tagging. We compare bi-LSTMs to traditional POS taggers across languages and data sizes. We also present a novel bi-LSTM model, which combines the POS tagging loss function with an auxiliary loss function that accounts for rare words. The model obtains state-of-the-art performance across 22 languages, and works especially well for morphologically complex languages. Our analysis suggests that bi-LSTMs are less sensitive to training data size and label corruptions (at small noise levels) than previously assumed.

##### Abstract (translated by Google)
双向长期短期记忆（bi-LSTM）网络最近已经证明对于各种NLP序列建模任务是成功的，但是对输入表示，目标语言，数据集大小和标签噪声的依赖知之甚少。我们解决这些问题，并评估bi-LSTM的字词，字符和unicode字节嵌入POS标记。我们将双LSTM与跨语言和数据大小的传统POS标记器进行比较。我们还提出了一种新型的双LSTM模型，该模型将POS标记损失函数与考虑稀有词的辅助损失函数相结合。该模型获得了22种语言的最新性能，并且对形态复杂的语言特别有效。我们的分析表明，bi-LSTM对训练数据大小和标签损坏（在小噪声水平下）比先前假定的更不敏感。

##### URL
[https://arxiv.org/abs/1604.05529](https://arxiv.org/abs/1604.05529)

##### PDF
[https://arxiv.org/pdf/1604.05529](https://arxiv.org/pdf/1604.05529)

