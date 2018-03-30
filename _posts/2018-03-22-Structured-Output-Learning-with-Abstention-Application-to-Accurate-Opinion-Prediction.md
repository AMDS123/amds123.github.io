---
layout: post
title: "Structured Output Learning with Abstention: Application to Accurate Opinion Prediction"
date: 2018-03-22 13:48:30
categories: arXiv_AI
tags: arXiv_AI Review Prediction
author: Alexandre Garcia, Slim Essid, Chloé Clavel, Florence d'Alché-Buc
mathjax: true
---

* content
{:toc}

##### Abstract
Motivated by Supervised Opinion Analysis, we propose a novel framework devoted to Structured Output Learning with Abstention (SOLA). The structure prediction model is able to abstain from predicting some labels in the structured output at a cost chosen by the user in a flexible way. For that purpose, we decompose the problem into the learning of a pair of predictors, one devoted to structured abstention and the other, to structured output prediction. To compare fully labeled training data with predictions potentially containing abstentions, we define a wide class of asymmetric abstention-aware losses. Learning is achieved by surrogate regression in an appropriate feature space while prediction with abstention is performed by solving a new pre-image problem. Thus, SOLA extends recent ideas about Structured Output Prediction via surrogate problems and calibration theory and enjoys statistical guarantees on the resulting excess risk. Instantiated on a hierarchical abstention-aware loss, SOLA is shown to be relevant for fine-grained opinion mining and gives state-of-the-art results on this task. Moreover, the abstention-aware representations can be used to competitively predict user-review ratings based on a sentence-level opinion predictor.

##### Abstract (translated by Google)
受监督意见分析的启发，我们提出了一个专门用于结构化输出学习与弃权（SOLA）的新框架。结构预测模型能够以灵活的方式以用户选择的成本避免在结构化输出中预测一些标签。为此，我们将问题分解为一对预测变量的学习，一个致力于结构化弃权，另一个致力于结构化产出预测。为了将完全标记的训练数据与可能包含弃权的预测进行比较，我们定义了一大类不对称弃权意识损失。通过在适当的特征空间中进行替代回归来实现学习，而通过解决新的前像问题来执行弃权预测。因此，SOLA通过替代问题和校准理论扩展了最近关于结构化输出预测的想法，并对由此产生的超额风险提供统计保证。在分级弃权意识损失上实例化后，SOLA被证明与细粒度意见挖掘相关，并为此任务提供了最新的结果。此外，可以使用弃权意识表示来基于句子级意见预测器竞争性地预测用户评论评级。

##### URL
[https://arxiv.org/abs/1803.08355](https://arxiv.org/abs/1803.08355)

##### PDF
[https://arxiv.org/pdf/1803.08355](https://arxiv.org/pdf/1803.08355)

