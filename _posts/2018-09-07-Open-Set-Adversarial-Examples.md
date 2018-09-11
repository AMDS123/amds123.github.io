---
layout: post
title: "Open Set Adversarial Examples"
date: 2018-09-07 21:29:32
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge Classification Recognition
author: Zhedong Zheng, Liang Zheng, Zhilan Hu, Yi Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Adversarial examples in recent works target at closed set recognition systems, in which the training and testing classes are identical. In real-world scenarios, however, the testing classes may have limited, if any, overlap with the training classes, a problem named open set recognition. To our knowledge, the community does not have a specific design of adversarial examples targeting at this practical setting. Arguably, the new setting compromises traditional closed set attack methods in two aspects. First, closed set attack methods are based on classification and target at classification as well, but the open set problem suggests a different task, \emph{i.e.,} retrieval. It is undesirable that the generation mechanism of closed set recognition is different from the aim of open set recognition. Second, given that the query image is usually of an unseen class, predicting its category from the training classes is not reasonable, which leads to an inferior adversarial gradient. In this work, we view open set recognition as a retrieval task and propose a new approach, Opposite-Direction Feature Attack (ODFA), to generate adversarial examples / queries. When using an attacked example as query, we aim that the true matches be ranked as low as possible. In addressing the two limitations of closed set attack methods, ODFA directly works on the features for retrieval. The idea is to push away the feature of the adversarial query in the opposite direction of the original feature. Albeit simple, ODFA leads to a larger drop in Recall@K and mAP than the close-set attack methods on two open set recognition datasets, \emph{i.e.,} Market-1501 and CUB-200-2011. We also demonstrate that the attack performance of ODFA is not evidently superior to the state-of-the-art methods under closed set recognition (Cifar-10), suggesting its specificity for open set problems.

##### Abstract (translated by Google)
最近工作中的对抗性示例以闭集识别系统为目标，其中训练和测试类是相同的。然而，在实际场景中，测试类可能与训练类重叠（如果有的话），这个问题称为开放集识别。据我们所知，社区没有针对此实际环境的具体对抗性示例设计。可以说，新设置在两个方面损害了传统的闭集攻击方法。首先，封闭集攻击方法也基于分类和目标进行分类，但是开集问题提出了一个不同的任务，即\ emph {即}检索。不希望闭集识别的生成机制与开集识别的目的不同。其次，鉴于查询图像通常是看不见的类，从训练类中预测其类别是不合理的，这导致较差的对抗梯度。在这项工作中，我们将开放集识别视为检索任务，并提出一种新方法，即相反方向特征攻击（ODFA），以生成对抗性示例/查询。当使用受攻击的示例作为查询时，我们的目标是将真实匹配排列为尽可能低。在解决闭集攻击方法的两个局限性时，ODFA直接处理用于检索的特征。我们的想法是在原始特征的相反方向上推开对抗性查询的特征。虽然简单，ODFA导致Recall @ K和mAP的下降比两个开放集识别数据集中的近集攻击方法更大，\ emph {,,} Market-1501和CUB-200-2011。我们还证明了ODFA的攻击性能并不明显优于封闭集识别（Cifar-10）下的最新方法，这表明它对开集问题的特异性。

##### URL
[http://arxiv.org/abs/1809.02681](http://arxiv.org/abs/1809.02681)

##### PDF
[http://arxiv.org/pdf/1809.02681](http://arxiv.org/pdf/1809.02681)

