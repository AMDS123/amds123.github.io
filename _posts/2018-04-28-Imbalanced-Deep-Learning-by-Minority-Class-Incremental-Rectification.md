---
layout: post
title: "Imbalanced Deep Learning by Minority Class Incremental Rectification"
date: 2018-04-28 22:36:19
categories: arXiv_CV
tags: arXiv_CV Sparse Deep_Learning
author: Qi Dong, Shaogang Gong, Xiatian Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
Model learning from class imbalanced training data is a long-standing and significant challenge for machine learning. In particular, existing deep learning methods consider mostly either class balanced data or moderately imbalanced data in model training, and ignore the challenge of learning from significantly imbalanced training data. To address this problem, we formulate a class imbalanced deep learning model based on batch-wise incremental minority (sparsely sampled) class rectification by hard sample mining in majority (frequently sampled) classes during model training. This model is designed to minimise the dominant effect of majority classes by discovering sparsely sampled boundaries of minority classes in an iterative batch-wise learning process. To that end, we introduce a Class Rectification Loss (CRL) function that can be deployed readily in deep network architectures. Extensive experimental evaluations are conducted on three imbalanced person attribute benchmark datasets (CelebA, X-Domain, DeepFashion) and one balanced object category benchmark dataset (CIFAR-100). These experimental results demonstrate the performance advantages and model scalability of the proposed batch-wise incremental minority class rectification model over the existing state-of-the-art models for addressing the problem of imbalanced data learning.

##### Abstract (translated by Google)
从班级失衡的培训数据中学习模型是机器学习长期存在的重大挑战。特别是，现有的深度学习方法主要考虑模型训练中的类平衡数据或适度不平衡的数据，忽略了从显着不平衡的训练数据中学习的挑战。为了解决这个问题，我们在模型训练过程中基于大部分（频繁采样）类别的硬采样挖掘基于分批增量少数（稀疏采样）类别纠正来制定类别不均衡深度学习模型。该模型旨在通过在迭代分批学习过程中发现少数类别的稀疏采样边界来最大限度地减少大多数类别的主导效应。为此，我们引入了可在深度网络架构中轻松部署的类整流损失（CRL）功能。对三个不平衡人员属性基准数据集（CelebA，X-Domain，DeepFashion）和一个平衡对象类别基准数据集（CIFAR-100）进行了广泛的实验评估。这些实验结果证明了提出的分批增量少数类整流模型相对于现有最先进模型的性能优势和模型可扩展性，以解决不平衡数据学习问题。

##### URL
[https://arxiv.org/abs/1804.10851](https://arxiv.org/abs/1804.10851)

##### PDF
[https://arxiv.org/pdf/1804.10851](https://arxiv.org/pdf/1804.10851)

