---
layout: post
title: "Object category learning and retrieval with weak supervision"
date: 2018-01-26 21:47:59
categories: arXiv_CV
tags: arXiv_CV Segmentation Embedding
author: Steven Hickson, Anelia Angelova, Irfan Essa, Rahul Sukthankar
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the problem of retrieving objects from image data and learning to classify them into meaningful semantic categories with minimal supervision. To that end, we propose a fully differentiable unsupervised deep clustering approach to learn semantic classes in an end-to-end fashion without individual class labeling using only unlabeled object proposals. The key contributions of our work are 1) a kmeans clustering objective where the clusters are learned as parameters of the network and are represented as memory units, and 2) simultaneously building a feature representation, or embedding, while learning to cluster it. This approach shows promising results on two popular computer vision datasets: on CIFAR10 for clustering objects, and on the more complex and challenging Cityscapes dataset for semantically discovering classes which visually correspond to cars, people, and bicycles. Currently, the only supervision provided is segmentation objectness masks, but this method can be extended to use an unsupervised objectness-based object generation mechanism which will make the approach completely unsupervised.

##### Abstract (translated by Google)
我们考虑从图像数据中检索对象的问题，并学习将它们分类为有意义的语义类别，而只需要最少的监督。为此，我们提出了一种完全可区分的无监督深度聚类方法，以端到端的方式学习语义类，而无需使用未标记的对象提议进行单独的类标注。我们工作的主要贡献是1）kmeans聚类的目标，其中集群学习作为网络的参数，并表示为内存单元，2）同时建立一个特征表示，或嵌入，同时学习聚类它。这种方法在两个流行的计算机视觉数据集上表现出令人鼓舞的结果：在用于聚类对象的CIFAR10上以及用于在语义上发现与汽车，人和自行车视觉对应的类的更复杂和具有挑战性的Cityscapes数据集上。目前，唯一提供的监督是分割对象掩码，但是这种方法可以扩展到使用无监督的基于对象的对象生成机制，这将使得方法完全无监督。

##### URL
[http://arxiv.org/abs/1801.08985](http://arxiv.org/abs/1801.08985)

##### PDF
[http://arxiv.org/pdf/1801.08985](http://arxiv.org/pdf/1801.08985)

