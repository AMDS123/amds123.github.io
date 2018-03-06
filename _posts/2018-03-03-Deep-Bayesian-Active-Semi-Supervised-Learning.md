---
layout: post
title: "Deep Bayesian Active Semi-Supervised Learning"
date: 2018-03-03 19:13:40
categories: arXiv_CV
tags: arXiv_CV CNN Classification Deep_Learning
author: Matthias Rottmann, Karsten Kahl, Hanno Gottschalk
mathjax: true
---

* content
{:toc}

##### Abstract
In many applications the process of generating label information is expensive and time consuming. We present a new method that combines active and semi-supervised deep learning to achieve high generalization performance from a deep convolutional neural network with as few known labels as possible. In a setting where a small amount of labeled data as well as a large amount of unlabeled data is available, our method first learns the labeled data set. This initialization is followed by an expectation maximization algorithm, where further training reduces classification entropy on the unlabeled data by targeting a low entropy fit which is consistent with the labeled data. In addition the algorithm asks at a specified frequency an oracle for labels of data with entropy above a certain entropy quantile. Using this active learning component we obtain an agile labeling process that achieves high accuracy, but requires only a small amount of known labels. For the MNIST dataset we report an error rate of 2.06% using only 300 labels and 1.06% for 1000 labels. These results are obtained without employing any special network architecture or data augmentation.

##### Abstract (translated by Google)
在许多应用中，生成标签信息的过程是昂贵和耗时的。我们提出了一种新方法，它结合了主动和半监督深度学习，从尽可能少的已知标签的深度卷积神经网络中实现高泛化性能。在少量标记数据以及大量未标记数据的情况下，我们的方法首先学习标记数据集。该初始化之后是期望最大化算法，其中进一步的训练通过针对与所标记的数据一致的低熵拟合来降低未标记数据上的分类熵。此外，该算法以特定频率向特定熵分位数以上的熵提供数据标签。使用这个主动学习组件，我们获得了一个敏捷标签过程，可以实现高精度，但只需要少量已知标签。对于MNIST数据集，我们报告错误率为2.06％，仅使用300个标签，1.06％为1000个标签。无需使用任何特殊的网络架构或数据增强就可以获得这些结果。

##### URL
[http://arxiv.org/abs/1803.01216](http://arxiv.org/abs/1803.01216)

##### PDF
[http://arxiv.org/pdf/1803.01216](http://arxiv.org/pdf/1803.01216)

