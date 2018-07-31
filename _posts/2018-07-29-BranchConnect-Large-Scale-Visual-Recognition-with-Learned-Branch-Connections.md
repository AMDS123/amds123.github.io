---
layout: post
title: "BranchConnect: Large-Scale Visual Recognition with Learned Branch Connections"
date: 2018-07-29 18:56:25
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
我们引入了一种用于大规模图像分类的体系结构，该体系结构使得能够对不同类别的单独视觉特征进行端到端学习以进行区分。所提出的模型由形状像树的深CNN组成。树的主干包括所有类共有的卷积层序列。然后，分支分成多个分支，实现并行特征提取器，最终通过学习的门控连接连接到最终分类层。这些学习的门确定每个单独的类要使用的特征子集。这样的方案自然地鼓励通过单独的分支学习异构的一组专用特征，并且它允许每个类使用对其识别最佳的特征子集。我们通过将文献中的几个流行的CNN重塑为我们提出的架构来展示我们提出的方法的一般性。我们在CIFAR100，CIFAR10和Synth数据集上的实验表明，在每种情况下，我们得到的模型比原始CNN在准确度方面有显着提高。我们的实证分析还表明，我们的方案是一种有益的正规化形式，可以提高泛化绩效。

##### URL
[http://arxiv.org/abs/1704.06010](http://arxiv.org/abs/1704.06010)

##### PDF
[http://arxiv.org/pdf/1704.06010](http://arxiv.org/pdf/1704.06010)

