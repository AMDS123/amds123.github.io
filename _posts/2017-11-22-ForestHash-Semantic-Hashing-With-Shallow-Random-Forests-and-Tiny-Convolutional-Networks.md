---
layout: post
title: "ForestHash: Semantic Hashing With Shallow Random Forests and Tiny Convolutional Networks"
date: 2017-11-22 16:16:42
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval CNN Image_Classification Classification
author: Qiang Qiu, Jose Lezama, Alex Bronstein, Guillermo Sapiro
mathjax: true
---

* content
{:toc}

##### Abstract
Hash codes are efficient data representations for coping with the ever growing amounts of data. In this paper, we introduce a random forest semantic hashing scheme that embeds tiny convolutional neural networks (CNN) into shallow random forests, with near-optimal information-theoretic code aggregation among trees. We start with a simple hashing scheme, where random trees in a forest act as hashing functions by setting `1' for the visited tree leaf, and `0' for the rest. We show that traditional random forests fail to generate hashes that preserve the underlying similarity between the trees, rendering the random forests approach to hashing challenging. To address this, we propose to first randomly group arriving classes at each tree split node into two groups, obtaining a significantly simplified two-class classification problem, which can be handled using a light-weight CNN weak learner. Such random class grouping scheme enables code uniqueness by enforcing each class to share its code with different classes in different trees. A non-conventional low-rank loss is further adopted for the CNN weak learners to encourage code consistency by minimizing intra-class variations and maximizing inter-class distance for the two random class groups. Finally, we introduce an information-theoretic approach for aggregating codes of individual trees into a single hash code, producing a near-optimal unique hash for each class. The proposed approach significantly outperforms state-of-the-art hashing methods for image retrieval tasks on large-scale public datasets, while performing at the level of other state-of-the-art image classification techniques while utilizing a more compact and efficient scalable representation. This work proposes a principled and robust procedure to train and deploy in parallel an ensemble of light-weight CNNs, instead of simply going deeper.

##### Abstract (translated by Google)
哈希代码是应对不断增长的数据量的有效数据表示。在本文中，我们引入了一个随机森林语义哈希方案，将微小的卷积神经网络（CNN）嵌入到浅层随机森林中，在树之间进行近乎最优的信息理论代码聚合。我们从一个简单的散列方案开始，其中森林中的随机树作为散列函数，为访问树叶设置“1”，其余为“0”。我们表明，传统的随机森林不能生成散列，保持树之间的基本相似性，使随机森林接近哈希挑战。为了解决这个问题，我们建议首先在每个树分裂节点上将到达的类别随机分为两组，得到一个显着简化的两类分类问题，这个问题可以用一个轻量级的CNN弱学习器来处理。这样的随机类分组方案通过强制每个类与不同树中的不同类共享其代码来实现代码唯一性。 CNN弱学习者进一步采用非常规的低秩丢失来鼓励代码的一致性，即通过最小化类内变异和最大化两个随机类群之间的类间距离。最后，我们引入一种信息论的方法来将单个树的代码聚合成一个散列码，为每个类生成一个接近最佳的唯一散列。所提出的方法明显优于用于大规模公共数据集上的图像检索任务的最先进的哈希方法，同时利用其他最先进的图像分类技术的水平来执行，同时利用更紧凑和高效的可扩展表示。这项工作提出了一个原则性和强大的程序来训练和平行部署轻量级有线电视网络，而不是简单地深入。

##### URL
[https://arxiv.org/abs/1711.08364](https://arxiv.org/abs/1711.08364)

##### PDF
[https://arxiv.org/pdf/1711.08364](https://arxiv.org/pdf/1711.08364)

