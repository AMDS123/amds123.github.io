---
layout: post
title: "Stochastic Learning of Multi-Instance Dictionary for Earth Mover's Distance based Histogram Comparison"
date: 2016-09-03 11:19:39
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Regularization Optimization Classification Relation
author: Jihong Fan, Ru-Ze Liang
mathjax: true
---

* content
{:toc}

##### Abstract
Dictionary plays an important role in multi-instance data representation. It maps bags of instances to histograms. Earth mover's distance (EMD) is the most effective histogram distance metric for the application of multi-instance retrieval. However, up to now, there is no existing multi-instance dictionary learning methods designed for EMD based histogram comparison. To fill this gap, we develop the first EMD-optimal dictionary learning method using stochastic optimization method. In the stochastic learning framework, we have one triplet of bags, including one basic bag, one positive bag, and one negative bag. These bags are mapped to histograms using a multi-instance dictionary. We argue that the EMD between the basic histogram and the positive histogram should be smaller than that between the basic histogram and the negative histogram. Base on this condition, we design a hinge loss. By minimizing this hinge loss and some regularization terms of the dictionary, we update the dictionary instances. The experiments over multi-instance retrieval applications shows its effectiveness when compared to other dictionary learning methods over the problems of medical image retrieval and natural language relation classification.

##### Abstract (translated by Google)
词典在多实例数据表示中起着重要的作用。它将实例的包映射到直方图。地球移动者的距离（EMD）是应用多实例检索的最有效的直方图距离度量。然而，到目前为止，还没有为基于EMD的直方图比较而设计的多实例字典学习方法。为了填补这个空白，我们使用随机优化方法开发了第一个EMD优化的字典学习方法。在随机学习框架中，我们有一个三重包，包括一个基本包，一个正面包，一个负面包。这些行李使用多实例字典映射到直方图。我们认为基本直方图和正直方图之间的EMD应该小于基本直方图和负直方图之间的EMD。基于这个条件，我们设计一个铰链损失。通过最小化这个铰链损失和字典的一些正则化术语，我们更新字典实例。与其他字典学习方法相比，多实例检索应用的实验在医学图像检索和自然语言关系分类问题上显示出其有效性。

##### URL
[https://arxiv.org/abs/1609.00817](https://arxiv.org/abs/1609.00817)

##### PDF
[https://arxiv.org/pdf/1609.00817](https://arxiv.org/pdf/1609.00817)

