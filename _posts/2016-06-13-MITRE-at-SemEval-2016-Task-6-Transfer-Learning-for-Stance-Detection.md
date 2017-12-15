---
layout: post
title: "MITRE at SemEval-2016 Task 6: Transfer Learning for Stance Detection"
date: 2016-06-13 00:12:49
categories: arXiv_CL
tags: arXiv_CL Embedding Transfer_Learning Language_Model Prediction Detection
author: Guido Zarrella, Amy Marsh
mathjax: true
---

* content
{:toc}

##### Abstract
We describe MITRE's submission to the SemEval-2016 Task 6, Detecting Stance in Tweets. This effort achieved the top score in Task A on supervised stance detection, producing an average F1 score of 67.8 when assessing whether a tweet author was in favor or against a topic. We employed a recurrent neural network initialized with features learned via distant supervision on two large unlabeled datasets. We trained embeddings of words and phrases with the word2vec skip-gram method, then used those features to learn sentence representations via a hashtag prediction auxiliary task. These sentence vectors were then fine-tuned for stance detection on several hundred labeled examples. The result was a high performing system that used transfer learning to maximize the value of the available training data.

##### Abstract (translated by Google)
我们描述MITRE提交给SemEval-2016任务6，检测Tweets中的立场。这项工作取得了监督站立检测任务A的最高分，在评估推特作者是赞成还是反对某个主题时，平均得分为67.8。我们采用了一个循环神经网络，通过对两个大型未标记数据集进行远程监督，学习了特征。我们用word2vec skip-gram方法训练单词和短语的嵌入，然后使用这些特征通过标签预测辅助任务学习句子表示。然后对这些句子向量进行微调，以便在数百个标记的例子中进行立场检测。结果是一个高效的系统，使用转移学习来最大化可用的训练数据的价值。

##### URL
[https://arxiv.org/abs/1606.03784](https://arxiv.org/abs/1606.03784)

##### PDF
[https://arxiv.org/pdf/1606.03784](https://arxiv.org/pdf/1606.03784)

