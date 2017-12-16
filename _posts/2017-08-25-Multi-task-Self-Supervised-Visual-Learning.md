---
layout: post
title: "Multi-task Self-Supervised Visual Learning"
date: 2017-08-25 18:52:17
categories: arXiv_CV
tags: arXiv_CV Regularization Classification Prediction Detection
author: Carl Doersch, Andrew Zisserman
mathjax: true
---

* content
{:toc}

##### Abstract
We investigate methods for combining multiple self-supervised tasks--i.e., supervised tasks where data can be collected without manual labeling--in order to train a single visual representation. First, we provide an apples-to-apples comparison of four different self-supervised tasks using the very deep ResNet-101 architecture. We then combine tasks to jointly train a network. We also explore lasso regularization to encourage the network to factorize the information in its representation, and methods for "harmonizing" network inputs in order to learn a more unified representation. We evaluate all methods on ImageNet classification, PASCAL VOC detection, and NYU depth prediction. Our results show that deeper networks work better, and that combining tasks--even via a naive multi-head architecture--always improves performance. Our best joint network nearly matches the PASCAL performance of a model pre-trained on ImageNet classification, and matches the ImageNet network on NYU depth prediction.

##### Abstract (translated by Google)
我们研究组合多个自我监督任务的方法 - 即监督任务，在这些任务中，数据可以在没有人工标记的情况下被收集 - 以训练一个单一的视觉表示。首先，我们使用深度ResNet-101架构提供了四种不同的自我监督任务的苹果与苹果的比较。然后我们合并任务来共同训练一个网络。我们还探索套索正规化，鼓励网络将其表示中的信息因子分解，以及“协调”网络输入的方法，以便学习更统一的表示。我们评估ImageNet分类，PASCAL VOC检测和NYU深度预测的所有方法。我们的研究结果表明，更深层次的网络能够更好地发挥作用，即使通过一个天真的多头架构，任务的结合也会提高性能。我们最好的联合网络几乎匹配在ImageNet分类上预先训练的模型的PASCAL性能，并在纽约大学深度预测上匹配ImageNet网络。

##### URL
[https://arxiv.org/abs/1708.07860](https://arxiv.org/abs/1708.07860)

##### PDF
[https://arxiv.org/pdf/1708.07860](https://arxiv.org/pdf/1708.07860)

