---
layout: post
title: "Differentially Private Distributed Learning for Language Modeling Tasks"
date: 2017-12-20 13:28:13
categories: arXiv_CL
tags: arXiv_CL Knowledge Face Transfer_Learning Language_Model Prediction
author: Vadim Popov, Mikhail Kudinov, Irina Piontkovskaya, Petr Vytovtov, Alex Nevidomsky
mathjax: true
---

* content
{:toc}

##### Abstract
One of the big challenges in machine learning applications is that training data can be different from the real-world data faced by the algorithm. In language modeling, the language of users (e.g. in private messaging) could change in a year and be completely different from what we observe in publicly available data. At the same time, public data can be used for obtaining general knowledge (i.e. general model of English). We study approaches to distributed fine-tuning of a general model on user private data with the additional requirement of maintaining the quality on the general data. Our experiments demonstrate that a technique based on model averaging and random rehearsal outperforms an approach based on transfer learning, and show that the proposed method improves prediction quality in a reasonable time. The procedure leads to an almost 70% perplexity reduction and 8.7 percentage point improvement in keystroke saving rate on informal English texts compared to a basic model trained on Wikipedia. We also propose an experimental framework for evaluating differential privacy of distributed training of language models and show that our approach has good privacy guarantees.

##### Abstract (translated by Google)
机器学习应用程序面临的一个重大挑战是训练数据可能与算法所面临的实际数据不同。在语言建模中，用户的语言（例如私人消息）可能会在一年内发生变化，与我们在公开数据中观察到的情况完全不同。与此同时，公共数据可以用来获取一般知识（即英语的一般模式）。我们研究在用户私人数据上分布式微调通用模型的方法，同时还要求保持一般数据的质量。我们的实验表明，基于模型平均和随机排练的技术优于基于转移学习的方法，并且表明所提出的方法在合理的时间内提高了预测质量。相比于在维基百科上训练的基本模型，该程序导致非正式英语文本的按键保存率降低了近70％的困惑度和8.7个百分点的提高。我们还提出了一个评估语言模型的分布式培训的差异隐私的实验框架，并表明我们的方法具有良好的隐私保证。

##### URL
[https://arxiv.org/abs/1712.07473](https://arxiv.org/abs/1712.07473)

##### PDF
[https://arxiv.org/pdf/1712.07473](https://arxiv.org/pdf/1712.07473)

