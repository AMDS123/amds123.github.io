---
layout: post
title: "Topical Stance Detection for Twitter: A Two-Phase LSTM Model Using Attention"
date: 2018-01-09 17:00:24
categories: arXiv_CL
tags: arXiv_CL Sentiment Attention RNN Deep_Learning Detection
author: Kuntal Dey, Ritvik Shrivastava, Saroj Kaushik
mathjax: true
---

* content
{:toc}

##### Abstract
The topical stance detection problem addresses detecting the stance of the text content with respect to a given topic: whether the sentiment of the given text content is in FAVOR of (positive), is AGAINST (negative), or is NONE (neutral) towards the given topic. Using the concept of attention, we develop a two-phase solution. In the first phase, we classify subjectivity - whether a given tweet is neutral or subjective with respect to the given topic. In the second phase, we classify sentiment of the subjective tweets (ignoring the neutral tweets) - whether a given subjective tweet has a FAVOR or AGAINST stance towards the topic. We propose a Long Short-Term memory (LSTM) based deep neural network for each phase, and embed attention at each of the phases. On the SemEval 2016 stance detection Twitter task dataset, we obtain a best-case macro F-score of 68.84% and a best-case accuracy of 60.2%, outperforming the existing deep learning based solutions. Our framework, T-PAN, is the first in the topical stance detection literature, that uses deep learning within a two-phase architecture.

##### Abstract (translated by Google)
局部立场检测问题解决了针对给定主题检测文本内容的姿态：给定文本内容的情绪是（FAVOR）是（正），是反对（负）还是无（中立）给定的主题。使用注意力的概念，我们开发了一个两阶段的解决方案。在第一阶段，我们对主观性进行分类 - 给定的推文对于给定的主题是中性的还是主观的。在第二阶段，我们将主观鸣叫（忽略中立鸣叫）的情绪分类 - 给定的主观鸣叫对于该主题是否具有正面或反面的立场。我们提出了一个基于长期短期记忆（LSTM）的深度神经网络，并且在每个阶段都会引起注意。在2016年的SemEval立场检测Twitter任务数据集中，我们获得了68.84％的最佳情况宏观F分数和60.2％的最佳情况精度，优于现有的基于深度学习的解决方案。我们的框架，T-PAN，是第一个在局部立场检测文献，在两阶段架构内使用深度学习。

##### URL
[http://arxiv.org/abs/1801.03032](http://arxiv.org/abs/1801.03032)

##### PDF
[http://arxiv.org/pdf/1801.03032](http://arxiv.org/pdf/1801.03032)

