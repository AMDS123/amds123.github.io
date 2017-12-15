---
layout: post
title: "Bandit Structured Prediction for Learning from Partial Feedback in Statistical Machine Translation"
date: 2016-01-18 11:09:02
categories: arXiv_SD
tags: arXiv_SD Prediction
author: Artem Sokolov, Stefan Riezler, Tanguy Urvoy
mathjax: true
---

* content
{:toc}

##### Abstract
We present an approach to structured prediction from bandit feedback, called Bandit Structured Prediction, where only the value of a task loss function at a single predicted point, instead of a correct structure, is observed in learning. We present an application to discriminative reranking in Statistical Machine Translation (SMT) where the learning algorithm only has access to a 1-BLEU loss evaluation of a predicted translation instead of obtaining a gold standard reference translation. In our experiment bandit feedback is obtained by evaluating BLEU on reference translations without revealing them to the algorithm. This can be thought of as a simulation of interactive machine translation where an SMT system is personalized by a user who provides single point feedback to predicted translations. Our experiments show that our approach improves translation quality and is comparable to approaches that employ more informative feedback in learning.

##### Abstract (translated by Google)
我们提出了一个从强盗反馈的结构化预测方法，称为Bandit结构预测，其中只有一个预测点的任务损失函数的值，而不是一个正确的结构，在学习中被观察到。在统计机器翻译（SMT）中，我们提出了一种应用于歧视性重排的方法，其中学习算法只能访问预测翻译的1-BLEU损失评估，而不是获得黄金标准参考翻译。在我们的实验中，通过在参考译文上评估BLEU而不将其暴露给算法，获得了盗匪反馈。这可以被认为是交互式机器翻译的模拟，其中SMT系统由向预测翻译提供单点反馈的用户进行个性化。我们的实验表明，我们的方法提高了翻译质量，并与在学习中使用更多信息反馈的方法相媲美。

##### URL
[https://arxiv.org/abs/1601.04468](https://arxiv.org/abs/1601.04468)

##### PDF
[https://arxiv.org/pdf/1601.04468](https://arxiv.org/pdf/1601.04468)

