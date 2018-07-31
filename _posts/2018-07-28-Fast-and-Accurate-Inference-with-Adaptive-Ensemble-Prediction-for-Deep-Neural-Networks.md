---
layout: post
title: "Fast and Accurate Inference with Adaptive Ensemble Prediction for Deep Neural Networks"
date: 2018-07-28 13:35:42
categories: arXiv_CV
tags: arXiv_CV Inference Prediction Relation
author: Hiroshi Inoue
mathjax: true
---

* content
{:toc}

##### Abstract
Ensembling multiple predictions is a widely-used technique to improve the accuracy of various machine learning tasks. One obvious drawback of the ensembling is its higher execution cost during inference. In this paper, we first describe our insights on relationship between the probability of the prediction and the effect of ensembling with current deep neural networks; ensembling does not help mispredictions for inputs predicted with a high probability even when there is a non-negligible number of mispredicted inputs. This finding motivates us to develop a new technique called adaptive ensemble prediction, which achieves the benefits of ensembling with much smaller additional execution costs. If the prediction for an input reaches a high enough probability on the basis of the confidence level, we stop ensembling for this input to avoid wasting computation power. We evaluated the adaptive ensembling by using various datasets and showed that it reduces the computation cost significantly while achieving similar accuracy to the naive ensembling. We also showed that our statistically rigorous confidence-level-based termination condition reduces the burden of the task-dependent parameter tuning compared to the naive termination based on the pre-defined threshold in addition to yielding a better accuracy with the same cost.

##### Abstract (translated by Google)
集成多个预测是一种广泛使用的技术，用于提高各种机器学习任务的准确性。集成的一个明显缺点是在推理期间其执行成本较高。在本文中，我们首先描述我们对预测概率与当前深度神经网络集成效果之间关系的见解;即使存在不可忽略的错误预测输入数量，集合也无助于错误预测输入的概率。这一发现促使我们开发出一种称为自适应集合预测的新技术，该技术以更小的额外执行成本实现集成的优势。如果输入的预测基于置信水平达到足够高的概率，则我们停止对该输入进行集合以避免浪费计算能力。我们通过使用各种数据集来评估自适应集成，并且表明它显着降低了计算成本，同时实现了与天真集合相似的精度。我们还表明，与基于预定阈值的朴素终止相比，我们统计上严格的基于置信度的终止条件减少了与任务相关的参数调整的负担，此外还以相同的成本产生更好的准确性。

##### URL
[http://arxiv.org/abs/1702.08259](http://arxiv.org/abs/1702.08259)

##### PDF
[http://arxiv.org/pdf/1702.08259](http://arxiv.org/pdf/1702.08259)

