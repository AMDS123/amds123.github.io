---
layout: post
title: "A Variational Feature Encoding Method of 3D Object for Probabilistic Semantic SLAM"
date: 2018-08-30 08:39:04
categories: arXiv_CV
tags: arXiv_CV Inference Classification SLAM Recognition
author: H. W. Yu, B. H. Lee
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a feature encoding method of complex 3D objects for high-level semantic features. Recent approaches to object recognition methods become important for semantic simultaneous localization and mapping (SLAM). However, there is a lack of consideration of the probabilistic observation model for 3D objects, as the shape of a 3D object basically follows a complex probability distribution. Furthermore, since the mobile robot equipped with a range sensor observes only a single view, much information of the object shape is discarded. These limitations are the major obstacles to semantic SLAM and view-independent loop closure using 3D object shapes as features. In order to enable the numerical analysis for the Bayesian inference, we approximate the true observation model of 3D objects to tractable distributions. Since the observation likelihood can be obtained from the generative model, we formulate the true generative model for 3D object with the Bayesian networks. To capture these complex distributions, we apply a variational auto-encoder. To analyze the approximated distributions and encoded features, we perform classification with maximum likelihood estimation and shape retrieval.

##### Abstract (translated by Google)
本文提出了一种用于高级语义特征的复杂三维对象的特征编码方法。最近的对象识别方法对于语义同时定位和映射（SLAM）变得重要。然而，由于3D对象的形状基本上遵循复杂的概率分布，因此缺乏对3D对象的概率观察模型的考虑。此外，由于配备有距离传感器的移动机器人仅观察单个视图，因此丢弃了对象形状的大量信息。这些限制是使用3D对象形状作为特征的语义SLAM和视图无关循环闭合的主要障碍。为了实现贝叶斯推理的数值分析，我们将三维物体的真实观测模型逼近易处理分布。由于观察可能性可以从生成模型中获得，我们用贝叶斯网络制定了3D对象的真实生成模型。为了捕获这些复杂的分布，我们应用了变分自动编码器。为了分析近似分布和编码特征，我们使用最大似然估计和形状检索进行分类。

##### URL
[http://arxiv.org/abs/1808.10180](http://arxiv.org/abs/1808.10180)

##### PDF
[http://arxiv.org/pdf/1808.10180](http://arxiv.org/pdf/1808.10180)

