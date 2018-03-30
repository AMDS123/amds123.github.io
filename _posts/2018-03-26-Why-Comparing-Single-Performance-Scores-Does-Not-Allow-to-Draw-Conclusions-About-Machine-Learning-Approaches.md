---
layout: post
title: "Why Comparing Single Performance Scores Does Not Allow to Draw Conclusions About Machine Learning Approaches"
date: 2018-03-26 13:35:14
categories: arXiv_AI
tags: arXiv_AI
author: Nils Reimers, Iryna Gurevych
mathjax: true
---

* content
{:toc}

##### Abstract
Developing state-of-the-art approaches for specific tasks is a major driving force in our research community. Depending on the prestige of the task, publishing it can come along with a lot of visibility. The question arises how reliable are our evaluation methodologies to compare approaches? One common methodology to identify the state-of-the-art is to partition data into a train, a development and a test set. Researchers can train and tune their approach on some part of the dataset and then select the model that worked best on the development set for a final evaluation on unseen test data. Test scores from different approaches are compared, and performance differences are tested for statistical significance. In this publication, we show that there is a high risk that a statistical significance in this type of evaluation is not due to a superior learning approach. Instead, there is a high risk that the difference is due to chance. For example for the CoNLL 2003 NER dataset we observed in up to 26% of the cases type I errors (false positives) with a threshold of p < 0.05, i.e., falsely concluding a statistically significant difference between two identical approaches. We prove that this evaluation setup is unsuitable to compare learning approaches. We formalize alternative evaluation setups based on score distributions.

##### Abstract (translated by Google)
开发针对特定任务的最先进方法是我们研究界的主要推动力。根据任务的声望，发布它可以带来很多可见性。问题是我们的评估方法在比较方法方面有多可靠？确定最新技术的一种常用方法是将数据划分为火车，开发和测试集。研究人员可以在数据集的某些部分训练和调整他们的方法，然后选择最适合开发集的模型，以便对未经验证的测试数据进行最终评估。比较不同方法的测试分数，并测试性能差异的统计显着性。在本出版物中，我们表明，这种评估的统计显着性不是由于优秀的学习方法所导致的高风险。相反，这种差异很有可能是偶然的。例如，对于CoNLL 2003 NER数据集，我们在高达26％的I型错误（假阳性）病例中观察到p <0.05的阈值，即错误地得出两种相同方法之间的统计学显着性差异。我们证明这个评估设置不适合比较学习方法。我们根据分数分布正式确定备选评估设置。

##### URL
[https://arxiv.org/abs/1803.09578](https://arxiv.org/abs/1803.09578)

##### PDF
[https://arxiv.org/pdf/1803.09578](https://arxiv.org/pdf/1803.09578)

