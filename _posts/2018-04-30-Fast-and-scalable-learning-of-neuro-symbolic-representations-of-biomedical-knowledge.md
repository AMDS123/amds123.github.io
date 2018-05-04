---
layout: post
title: "Fast and scalable learning of neuro-symbolic representations of biomedical knowledge"
date: 2018-04-30 09:54:12
categories: arXiv_AI
tags: arXiv_AI Knowledge_Graph Knowledge Embedding Represenation_Learning Classification Prediction Relation
author: Asan Agibetov, Matthias Samwald
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we address the problem of fast and scalable learning of neuro-symbolic representations for general biological knowledge. Based on a recently published comprehensive biological knowledge graph (Alshahrani, 2017) that was used for demonstrating neuro-symbolic representation learning, we show how to train fast (under 1 minute) log-linear neural embeddings of the entities. We utilize these representations as inputs for machine learning classifiers to enable important tasks such as biological link prediction. Classifiers are trained by concatenating learned entity embeddings to represent entity relations, and training classifiers on the concatenated embeddings to discern true relations from automatically generated negative examples. Our simple embedding methodology greatly improves on classification error compared to previously published state-of-the-art results, yielding a maximum increase of $+0.28$ F-measure and $+0.22$ ROC AUC scores for the most difficult biological link prediction problem. Finally, our embedding approach is orders of magnitude faster to train ($\leq$ 1 minute vs. hours), much more economical in terms of embedding dimensions ($d=50$ vs. $d=512$), and naturally encodes the directionality of the asymmetric biological relations, that can be controlled by the order with which we concatenate the embeddings.

##### Abstract (translated by Google)
在这项工作中，我们解决了一般生物学知识的神经 - 符号表示的快速和可扩展学习问题。基于最近发布的用于演示神经符号表示学习的综合生物知识图表（Alshahrani，2017），我们展示了如何训练实体的快速（不到1分钟）对数线性神经嵌入。我们利用这些表示作为机器学习分类器的输入，以实现诸如生物链接预测等重要任务。分类器通过连接学习实体嵌入来表示实体关系以及在连接的嵌入上训练分类器以识别来自自动生成的否定示例的真实关系来进行训练。与以前发表的最新结果相比，我们简单的嵌入方法极大地改善了分类错误，最大增加了$ + 0.28 $ F-measure和$ + 0.22 $ ROC AUC分数，用于最难的生物链接预测问题。最后，我们的嵌入方法的训练速度要快几个数量级（$ \ leq $ 1分钟vs.小时），在嵌入维度（$ d = 50 $ vs $ d = 512 $）方面更经济，并且自然编码不对称生物关系的方向性，可以通过我们连接嵌入的顺序来控制。

##### URL
[https://arxiv.org/abs/1804.11105](https://arxiv.org/abs/1804.11105)

##### PDF
[https://arxiv.org/pdf/1804.11105](https://arxiv.org/pdf/1804.11105)

