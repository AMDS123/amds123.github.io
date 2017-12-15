---
layout: post
title: "EELECTION at SemEval-2017 Task 10: Ensemble of nEural Learners for kEyphrase ClassificaTION"
date: 2017-04-10 10:31:49
categories: arXiv_CL
tags: arXiv_CL Attention CNN RNN Classification Deep_Learning Relation
author: Steffen Eger, Erik-Lân Do Dinh, Ilia Kuznetsov, Masoud Kiaeeha, Iryna Gurevych
mathjax: true
---

* content
{:toc}

##### Abstract
This paper describes our approach to the SemEval 2017 Task 10: "Extracting Keyphrases and Relations from Scientific Publications", specifically to Subtask (B): "Classification of identified keyphrases". We explored three different deep learning approaches: a character-level convolutional neural network (CNN), a stacked learner with an MLP meta-classifier, and an attention based Bi-LSTM. From these approaches, we created an ensemble of differently hyper-parameterized systems, achieving a micro-F1-score of 0.63 on the test data. Our approach ranks 2nd (score of 1st placed system: 0.64) out of four according to this official score. However, we erroneously trained 2 out of 3 neural nets (the stacker and the CNN) on only roughly 15% of the full data, namely, the original development set. When trained on the full data (training+development), our ensemble has a micro-F1-score of 0.69. Our code is available from this https URL

##### Abstract (translated by Google)
本文描述了我们对2017年下半年任务10：“从科学出版物中提取关键词和关系”的方法，特别是对子任务（B）：“确定的关键字词的分类”。我们探索了三种不同的深度学习方法：字符级卷积神经网络（CNN），带有MLP元分类器的堆叠式学习器和基于注意力的双向LSTM。从这些方法中，我们创建了不同超参数化系统的集合，在测试数据上获得了0.63的微F1分数。我们的方法根据这个官方评分排在第二位（第一位系统得分：0.64）。然而，我们错误地在3个神经网络（堆垛机和CNN）上仅对大约15％的全部数据（即最初的开发集）进行了培训。在训练完整数据（训练+训练）后，我们的团队拥有0.69的微F1成绩。我们的代码可从此https网址获得

##### URL
[https://arxiv.org/abs/1704.02215](https://arxiv.org/abs/1704.02215)

##### PDF
[https://arxiv.org/pdf/1704.02215](https://arxiv.org/pdf/1704.02215)

