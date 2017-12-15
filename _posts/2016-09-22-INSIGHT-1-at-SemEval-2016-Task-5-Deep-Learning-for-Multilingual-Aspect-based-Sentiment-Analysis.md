---
layout: post
title: "INSIGHT-1 at SemEval-2016 Task 5: Deep Learning for Multilingual Aspect-based Sentiment Analysis"
date: 2016-09-22 10:04:18
categories: arXiv_CL
tags: arXiv_CL Sentiment Embedding CNN Classification Deep_Learning Detection
author: Sebastian Ruder, Parsa Ghaffari, John G. Breslin
mathjax: true
---

* content
{:toc}

##### Abstract
This paper describes our deep learning-based approach to multilingual aspect-based sentiment analysis as part of SemEval 2016 Task 5. We use a convolutional neural network (CNN) for both aspect extraction and aspect-based sentiment analysis. We cast aspect extraction as a multi-label classification problem, outputting probabilities over aspects parameterized by a threshold. To determine the sentiment towards an aspect, we concatenate an aspect vector with every word embedding and apply a convolution over it. Our constrained system (unconstrained for English) achieves competitive results across all languages and domains, placing first or second in 5 and 7 out of 11 language-domain pairs for aspect category detection (slot 1) and sentiment polarity (slot 3) respectively, thereby demonstrating the viability of a deep learning-based approach for multilingual aspect-based sentiment analysis.

##### Abstract (translated by Google)
本文描述了我们基于深度学习的多语言基于方面的情感分析方法，作为SemEval 2016任务5的一部分。我们使用卷积神经网络（CNN）进行方面提取和基于方面的情感分析。我们将方面提取作为一个多标签分类问题，输出由一个阈值参数化的方面的概率。为了确定一个方面的情感，我们连接一个方面向量与每个单词的嵌入和应用卷积。我们的约束系统（不受英语约束）在所有语言和领域都取得了有竞争力的结果，分别针对方面类别检测（时隙1）和情感极性（时隙3）在11个语言域对中的第5个和第7个中分别放置第一个或第二个。展示了基于多种语言的基于方面的情感分析的深度学习方法的可行性。

##### URL
[https://arxiv.org/abs/1609.02748](https://arxiv.org/abs/1609.02748)

##### PDF
[https://arxiv.org/pdf/1609.02748](https://arxiv.org/pdf/1609.02748)

