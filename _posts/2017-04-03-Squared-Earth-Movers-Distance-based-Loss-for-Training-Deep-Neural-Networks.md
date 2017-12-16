---
layout: post
title: "Squared Earth Mover's Distance-based Loss for Training Deep Neural Networks"
date: 2017-04-03 02:30:57
categories: arXiv_CV
tags: arXiv_CV Classification Deep_Learning Prediction Relation
author: Le Hou, Chen-Ping Yu, Dimitris Samaras
mathjax: true
---

* content
{:toc}

##### Abstract
In the context of single-label classification, despite the huge success of deep learning, the commonly used cross-entropy loss function ignores the intricate inter-class relationships that often exist in real-life tasks such as age classification. In this work, we propose to leverage these relationships between classes by training deep nets with the exact squared Earth Mover's Distance (also known as Wasserstein distance) for single-label classification. The squared EMD loss uses the predicted probabilities of all classes and penalizes the miss-predictions according to a ground distance matrix that quantifies the dissimilarities between classes. We demonstrate that on datasets with strong inter-class relationships such as an ordering between classes, our exact squared EMD losses yield new state-of-the-art results. Furthermore, we propose a method to automatically learn this matrix using the CNN's own features during training. We show that our method can learn a ground distance matrix efficiently with no inter-class relationship priors and yield the same performance gain. Finally, we show that our method can be generalized to applications that lack strong inter-class relationships and still maintain state-of-the-art performance. Therefore, with limited computational overhead, one can always deploy the proposed loss function on any dataset over the conventional cross-entropy.

##### Abstract (translated by Google)
在单标签分类的背景下，尽管深度学习取得了巨大的成功，但常用的交叉熵损失函数却忽略了现实生活中常常存在的错综复杂的类间关系，如年龄分类。在这项工作中，我们建议利用精确平方的移动者的距离（也称为Wasserstein距离）训练深度网来进行单标签分类，从而利用这些类之间的关系。平方EMD损失使用所有类别的预测概率，并且根据量化类别之​​间的差异的地面距离矩阵来惩罚错误预测。我们证明，对于具有强大类间关系的数据集，如类之间的排序，我们精确的平方EMD损失产生新的最新的结果。此外，我们提出了一种在训练期间使用CNN自身特征自动学习这个矩阵的方法。我们表明，我们的方法可以有效地学习一个地面距离矩阵，没有类间关系的先验，并产生相同的性能增益。最后，我们展示了我们的方法可以推广到缺乏强大的类间关系，仍然保持最先进的性能的应用程序。因此，在有限的计算开销下，可以总是将所提出的损失函数在传统交叉熵上的任何数据集上进行部署。

##### URL
[https://arxiv.org/abs/1611.05916](https://arxiv.org/abs/1611.05916)

##### PDF
[https://arxiv.org/pdf/1611.05916](https://arxiv.org/pdf/1611.05916)

