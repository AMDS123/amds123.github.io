---
layout: post
title: "Unseen Class Discovery in Open-world Classification"
date: 2018-01-17 09:50:41
categories: arXiv_AI
tags: arXiv_AI Knowledge Classification
author: Lei Shu, Hu Xu, Bing Liu
mathjax: true
---

* content
{:toc}

##### Abstract
This paper concerns open-world classification, where the classifier not only needs to classify test examples into seen classes that have appeared in training but also reject examples from unseen or novel classes that have not appeared in training. Specifically, this paper focuses on discovering the hidden unseen classes of the rejected examples. Clearly, without prior knowledge this is difficult. However, we do have the data from the seen training classes, which can tell us what kind of similarity/difference is expected for examples from the same class or from different classes. It is reasonable to assume that this knowledge can be transferred to the rejected examples and used to discover the hidden unseen classes in them. This paper aims to solve this problem. It first proposes a joint open classification model with a sub-model for classifying whether a pair of examples belongs to the same or different classes. This sub-model can serve as a distance function for clustering to discover the hidden classes of the rejected examples. Experimental results show that the proposed model is highly promising.

##### Abstract (translated by Google)
本文关注开放世界的分类，其中分类器不仅需要将测试示例分类为已经出现在训练中的可见类，而且还拒绝未经训练的看不见的或新颖类的例子。具体而言，本文着重于发现被拒绝的例子的隐藏的看不见的类。显然，没有先验知识这是困难的。但是，我们确实有来自所看到的培训课程的数据，这可以告诉我们对于来自同一班级还是来自不同班级的例子，预计什么样的相似/差异。假设这种知识可以转化为被拒绝的例子，并用来发现隐藏在其中的看不见的类，这是合理的。本文旨在解决这个问题。它首先提出一个联合开放分类模型和一个子模型来分类一对例子是否属于相同或不同的类别。这个子模型可以作为聚类的距离函数来发现被拒绝的例子的隐藏类。实验结果表明，该模型是非常有前途的。

##### URL
[http://arxiv.org/abs/1801.05609](http://arxiv.org/abs/1801.05609)

##### PDF
[http://arxiv.org/pdf/1801.05609](http://arxiv.org/pdf/1801.05609)

