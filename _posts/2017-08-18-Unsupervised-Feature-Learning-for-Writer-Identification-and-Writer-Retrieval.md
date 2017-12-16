---
layout: post
title: "Unsupervised Feature Learning for Writer Identification and Writer Retrieval"
date: 2017-08-18 09:04:49
categories: arXiv_CV
tags: arXiv_CV CNN Classification Deep_Learning
author: Vincent Christlein, Martin Gropp, Stefan Fiel, Andreas Maier
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Convolutional Neural Networks (CNN) have shown great success in supervised classification tasks such as character classification or dating. Deep learning methods typically need a lot of annotated training data, which is not available in many scenarios. In these cases, traditional methods are often better than or equivalent to deep learning methods. In this paper, we propose a simple, yet effective, way to learn CNN activation features in an unsupervised manner. Therefore, we train a deep residual network using surrogate classes. The surrogate classes are created by clustering the training dataset, where each cluster index represents one surrogate class. The activations from the penultimate CNN layer serve as features for subsequent classification tasks. We evaluate the feature representations on two publicly available datasets. The focus lies on the ICDAR17 competition dataset on historical document writer identification (Historical-WI). We show that the activation features trained without supervision are superior to descriptors of state-of-the-art writer identification methods. Additionally, we achieve comparable results in the case of handwriting classification using the ICFHR16 competition dataset on historical Latin script types (CLaMM16).

##### Abstract (translated by Google)
深度卷积神经网络（CNN）在监督分类任务（如字符分类或约会）方面取得了巨大的成功。深度学习方法通​​常需要大量的注释培训数据，这在许多情况下是不可用的。在这些情况下，传统的方法通常比深度学习方法好或相当。在本文中，我们提出一种简单而有效的方式，以无监督的方式学习CNN激活特征。因此，我们使用代理类训练一个深度残差网络。代理类是通过聚类训练数据集创建的，其中每个聚类索引代表一个代理类。倒数第二个CNN层的激活作为后续分类任务的特征。我们评估两个公开可用数据集上的特征表示。重点在于ICDAR17历史文献作者鉴定竞争数据集（Historical-WI）。我们证明，没有监督的情况下训练的激活特征优于最先进的作者识别方法的描述。另外，在历史拉丁文字类型（CLaMM16）上使用ICFHR16竞争数据集进行手写分类时，我们取得了可比较的结果。

##### URL
[https://arxiv.org/abs/1705.09369](https://arxiv.org/abs/1705.09369)

##### PDF
[https://arxiv.org/pdf/1705.09369](https://arxiv.org/pdf/1705.09369)

