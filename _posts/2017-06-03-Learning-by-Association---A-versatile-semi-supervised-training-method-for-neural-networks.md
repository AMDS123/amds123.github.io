---
layout: post
title: "Learning by Association - A versatile semi-supervised training method for neural networks"
date: 2017-06-03 08:08:56
categories: arXiv_CV
tags: arXiv_CV Embedding Optimization Classification
author: Philip Häusser, Alexander Mordvintsev, Daniel Cremers
mathjax: true
---

* content
{:toc}

##### Abstract
In many real-world scenarios, labeled data for a specific machine learning task is costly to obtain. Semi-supervised training methods make use of abundantly available unlabeled data and a smaller number of labeled examples. We propose a new framework for semi-supervised training of deep neural networks inspired by learning in humans. "Associations" are made from embeddings of labeled samples to those of unlabeled ones and back. The optimization schedule encourages correct association cycles that end up at the same class from which the association was started and penalizes wrong associations ending at a different class. The implementation is easy to use and can be added to any existing end-to-end training setup. We demonstrate the capabilities of learning by association on several data sets and show that it can improve performance on classification tasks tremendously by making use of additionally available unlabeled data. In particular, for cases with few labeled data, our training scheme outperforms the current state of the art on SVHN.

##### Abstract (translated by Google)
在许多现实世界的场景中，用于特定机器学习任务的标记数据是昂贵的。半监督训练方法利用大量可用的未标记数据和少量标记的例子。我们提出了一个新的由人类学习启发的深度神经网络半监督训练框架。 “关联”是将标签样本嵌入到未标签样本的背面。优化时间表鼓励正确的关联周期，最终在同一个类别开始关联，并惩罚在不同类别结束的错误关联。该实现易于使用，可以添加到任何现有的端到端培训设置。我们展示了通过关联学习几个数据集的能力，并且表明它可以通过使用另外可用的未标记数据来极大地提高分类任务的性能。特别是对于标签数据较少的案例，我们的培训计划胜过了SVHN当前的技术水平。

##### URL
[https://arxiv.org/abs/1706.00909](https://arxiv.org/abs/1706.00909)

##### PDF
[https://arxiv.org/pdf/1706.00909](https://arxiv.org/pdf/1706.00909)

