---
layout: post
title: "BranchConnect: Large-Scale Visual Recognition with Learned Branch Connections"
date: 2017-04-24 14:28:40
categories: arXiv_CV
tags: arXiv_CV Regularization CNN Classification Recognition
author: Karim Ahmed, Lorenzo Torresani
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce an architecture for large-scale image categorization that enables the end-to-end learning of separate visual features for the different classes to distinguish. The proposed model consists of a deep CNN shaped like a tree. The stem of the tree includes a sequence of convolutional layers common to all classes. The stem then splits into multiple branches implementing parallel feature extractors, which are ultimately connected to the final classification layer via learned gated connections. These learned gates determine for each individual class the subset of features to use. Such a scheme naturally encourages the learning of a heterogeneous set of specialized features through the separate branches and it allows each class to use the subset of features that are optimal for its recognition. We show the generality of our proposed method by reshaping several popular CNNs from the literature into our proposed architecture. Our experiments on the CIFAR100, CIFAR10, and Synth datasets show that in each case our resulting model yields a substantial improvement in accuracy over the original CNN. Our empirical analysis also suggests that our scheme acts as a form of beneficial regularization improving generalization performance.

##### Abstract (translated by Google)
我们介绍了一个大规模图像分类的架构，使不同类别的视觉特征的端到端学习能够区分。所提出的模型由一个像树一样的深CNN形状组成。树的主干包括所有类共有的一系列卷积层。干然后分裂成多个分支执行并行特征提取器，最终通过学习的门控连接连接到最后的分类层。这些学习过的门为每个单独的类决定要使用的功能的子集。这样的方案自然鼓励通过单独的分支来学习异构的特定特征集合，并且允许每个类别使用对于其识别是最优的特征子集。我们通过将文献中几个受欢迎的CNN重塑为我们提出的架构来展示我们提出的方法的一般性。我们在CIFAR100，CIFAR10和Synth数据集上进行的实验表明，在每种情况下，我们所得到的模型都比原来的CNN在精度上有显着的提高。我们的实证分析也表明，我们的方案作为一种有益的正则化形式提高泛化性能。

##### URL
[https://arxiv.org/abs/1704.06010](https://arxiv.org/abs/1704.06010)

##### PDF
[https://arxiv.org/pdf/1704.06010](https://arxiv.org/pdf/1704.06010)

