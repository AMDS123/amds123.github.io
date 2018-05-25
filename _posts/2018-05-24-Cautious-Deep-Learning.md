---
layout: post
title: "Cautious Deep Learning"
date: 2018-05-24 00:17:24
categories: arXiv_AI
tags: arXiv_AI CNN Deep_Learning Prediction
author: Yotam Hechtlinger, Barnab&#xe1;s P&#xf3;czos, Larry Wasserman
mathjax: true
---

* content
{:toc}

##### Abstract
Most classifiers operate by selecting the maximum of an estimate of the conditional distribution $p(y|x)$ where $x$ stands for the features of the instance to be classified and $y$ denotes its label. This often results in a hubristic bias: overconfidence in the assignment of a definite label. Usually, the observations are concentrated on a small volume but the classifier provides definite predictions for the entire space. We propose constructing conformal prediction sets [vovk2005algorithmic] which contain a set of labels rather than a single label. These conformal prediction sets contain the true label with probability $1-\alpha$. Our construction is based on $p(x|y)$ rather than $p(y|x)$ which results in a classifier that is very cautious: it outputs the null set - meaning `I don't know' --- when the object does not resemble the training examples. An important property of our approach is that classes can be added or removed without having to retrain the classifier. We demonstrate the performance on the ImageNet ILSVRC dataset using high dimensional features obtained from state of the art convolutional neural networks.

##### Abstract (translated by Google)
大多数分类器通过选择条件分布$ p（y | x）$的估计的最大值来操作，其中$ x $表示要分类的实例的特征，$ y $表示其标签。这通常会导致傲慢的偏见：分配明确的标签过分自信。通常，观察集中在一个小的体积上，但分类器为整个空间提供确切的预测。我们提出构建共形预测集[vovk2005algorithmic]，它包含一组标签而不是单个标签。这些共形预测集合包含真实标签，概率为$ 1 \ alpha $。我们的构建基于$ p（x | y）$而不是$ p（y | x）$，这导致了一个非常谨慎的分类器：它输出空集 - 意思是“我不知道”---当对象不像训练样例时。我们的方法的一个重要特性是可以添加或删除类而不必重新训练分类器。我们使用从现有技术的卷积神经网络获得的高维特征来演示ImageNet ILSVRC数据集上的性能。

##### URL
[http://arxiv.org/abs/1805.09460](http://arxiv.org/abs/1805.09460)

##### PDF
[http://arxiv.org/pdf/1805.09460](http://arxiv.org/pdf/1805.09460)

