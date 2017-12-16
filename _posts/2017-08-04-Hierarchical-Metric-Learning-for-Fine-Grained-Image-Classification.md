---
layout: post
title: "Hierarchical Metric Learning for Fine Grained Image Classification"
date: 2017-08-04 13:38:46
categories: arXiv_CV
tags: arXiv_CV Image_Classification Classification
author: Akashdeep Goel, Biplab Banerjee
mathjax: true
---

* content
{:toc}

##### Abstract
This paper deals with the problem of fine-grained image classification and introduces the notion of hierarchical metric learning for the same. It is indeed challenging to categorize fine-grained image classes merely in terms of a single level classifier given the subtle inter-class visual differences. In order to tackle this problem, we propose a two stage framework where i) the image categories are represented hierarchically in terms of a binary tree structure where different subset of classes are present in the non-leaf nodes of the tree. This is accomplished in an automatic fashion considering the available training data in the visual domain, and ii) a (non-leaf) node specific metric learning is further deployed for the categories constituting a given node, thus enforcing better separation between both of its children. Subsequently, we construct (non-leaf) node specific binary classifiers in the learned metric spaces on which testing is henceforth carried out by following the outcomes of the classifiers sequence from root to leaf nodes of the tree. By separately focusing on the semantically similar classes at different levels of the hierarchy, it is expected that the classifiers in the learned metric spaces possess better discriminative capabilities than considering all the classes at a single go. Experimental results obtained on two challenging datasets (Oxford Flowers and Leeds Butterfly) establish the superiority of the proposed framework in comparison to the standard single metric learning based methods convincingly

##### Abstract (translated by Google)
本文讨论了细粒度图像分类问题，并介绍了分层度量学习的概念。将细粒度的图像类别分类为单一级别的分类器确实是具有挑战性的，因为给定了细微的类间视觉差异。为了解决这个问题，我们提出了一个两阶段的框架，其中：i）图像类别按照二叉树结构分层次地表示，其中在树的非叶节点中存在不同类别的子集。考虑到可视域中的可用训练数据，这是以自动方式完成的，并且ii）针对构成给定节点的类别进一步部署（非叶）节点特定度量学习，从而强化其两个子节点之间的更好的分离。随后，我们在学习的度量空间中构造（非叶子）节点特定的二进制分类器，在此之后通过跟随从树的根到叶节点的分类器序列的结果来执行测试。通过分别关注层次结构不同层次上的语义上相似的类别，期望在学习的度量空间中的分类器具有比一次考虑所有类别更好的区分能力。两个具有挑战性的数据集（牛津花和利兹蝴蝶）获得的实验结果确立了建议框架优于标准单一度量学习的方法相比，令人信服地

##### URL
[https://arxiv.org/abs/1708.01494](https://arxiv.org/abs/1708.01494)

##### PDF
[https://arxiv.org/pdf/1708.01494](https://arxiv.org/pdf/1708.01494)

