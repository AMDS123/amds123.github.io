---
layout: post
title: "Commonly Uncommon: Semantic Sparsity in Situation Recognition"
date: 2016-12-03 00:31:52
categories: arXiv_CV
tags: arXiv_CV Sparse Classification Prediction Recognition
author: Mark Yatskar, Vicente Ordonez, Luke Zettlemoyer, Ali Farhadi
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic sparsity is a common challenge in structured visual classification problems; when the output space is complex, the vast majority of the possible predictions are rarely, if ever, seen in the training set. This paper studies semantic sparsity in situation recognition, the task of producing structured summaries of what is happening in images, including activities, objects and the roles objects play within the activity. For this problem, we find empirically that most object-role combinations are rare, and current state-of-the-art models significantly underperform in this sparse data regime. We avoid many such errors by (1) introducing a novel tensor composition function that learns to share examples across role-noun combinations and (2) semantically augmenting our training data with automatically gathered examples of rarely observed outputs using web data. When integrated within a complete CRF-based structured prediction model, the tensor-based approach outperforms existing state of the art by a relative improvement of 2.11% and 4.40% on top-5 verb and noun-role accuracy, respectively. Adding 5 million images with our semantic augmentation techniques gives further relative improvements of 6.23% and 9.57% on top-5 verb and noun-role accuracy.

##### Abstract (translated by Google)
语义稀疏性是结构化视觉分类问题中常见的挑战;当输出空间很复杂时，绝大多数可能的预测在训练集中很少见到。本文研究了情景识别中的语义稀疏性，即对图像中发生的事件进行结构化总结，包括活动，对象以及对象在活动中扮演的角色。对于这个问题，我们从经验上发现，大多数对象 - 角色组合是罕见的，当前最先进的模型在这个稀疏的数据体系中显着表现不佳。我们避免了许多这样的错误：（1）引入了一个新颖的张量组合函数，学习如何在角色 - 名词组合之间共享实例;（2）使用Web数据自动收集很少观察到的输出的例子，从而语义上扩充训练数据。当整合到一个完整的基于CRF的结构化预测模型中时，基于张量的方法优于现有技术，分别比前5个动词和名词角色准确度分别提高2.11％和4.40％。使用语义增强技术添加500万图像，对前5个动词和名词角色的准确性提供了6.23％和9.57％的进一步相对改进。

##### URL
[https://arxiv.org/abs/1612.00901](https://arxiv.org/abs/1612.00901)

##### PDF
[https://arxiv.org/pdf/1612.00901](https://arxiv.org/pdf/1612.00901)

