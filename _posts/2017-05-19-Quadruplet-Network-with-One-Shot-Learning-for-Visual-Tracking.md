---
layout: post
title: "Quadruplet Network with One-Shot Learning for Visual Tracking"
date: 2017-05-19 23:37:54
categories: arXiv_CV
tags: arXiv_CV Tracking Object_Tracking Detection Relation
author: Xingping Dong, Jianbing Shen, Fatih Porikli
mathjax: true
---

* content
{:toc}

##### Abstract
As a discriminative method of one-shot learning, Siamese deep network allows recognizing an object from a single exemplar with the same class label. However, it does not take the advantage of the underlying structure and relationship among a multitude of instances since it only relies on pairs of instances for training. In this paper, we propose a quadruplet deep network to examine the potential connections among the training instances, aiming to achieve a more powerful representation. We design four shared networks that receive multi-tuple of instances as inputs and are connected by a novel loss function consisting of pair-loss and triplet-loss. According to the similarity metric, we select the most similar and the most dissimilar instances as the positive and negative inputs of triplet loss from each multi-tuple. We show that this scheme improves the training performance and convergence speed. Furthermore, we introduce a new weighted pair loss for an additional acceleration of the convergence. We demonstrate promising results for model-free tracking-by-detection of objects from a single initial exemplar in the Visual Object Tracking benchmark.

##### Abstract (translated by Google)
作为一次学习的判别方法，连体深度网络允许从具有相同类别标签的单个样本中识别对象。然而，它并没有利用多个实例之间的底层结构和关系，因为它只依赖于一对实例进行训练。在本文中，我们提出了一个四元组深度网络来检查训练实例之间的潜在联系，旨在实现更强大的表示。我们设计了四个共享网络，它们接收实例的多元组作为输入，并且通过由丢失对和三重丢失组成的新型丢失函数进行连接。根据相似性度量，我们从每个多元组中选择三元组亏损的正负输入的最相似和最不相似的实例。我们证明这个方案提高了训练性能和收敛速度。此外，我们引入一个新的加权对损失的额外加速收敛。我们展示了可视化对象跟踪基准测试中一个初始样本中对象的无模型跟踪检测的有希望的结果。

##### URL
[https://arxiv.org/abs/1705.07222](https://arxiv.org/abs/1705.07222)

##### PDF
[https://arxiv.org/pdf/1705.07222](https://arxiv.org/pdf/1705.07222)

