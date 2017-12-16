---
layout: post
title: "Deep Architectures for Face Attributes"
date: 2016-09-28 17:57:46
categories: arXiv_CV
tags: arXiv_CV Face CNN Classification Prediction
author: Tobi Baumgartner, Jack Culpepper
mathjax: true
---

* content
{:toc}

##### Abstract
We train a deep convolutional neural network to perform identity classification using a new dataset of public figures annotated with age, gender, ethnicity and emotion labels, and then fine-tune it for attribute classification. An optimal sharing pattern of computational resources within this network is determined by experiment, requiring only 1 G flops to produce all predictions. Rather than fine-tune by relearning weights in one additional layer after the penultimate layer of the identity network, we try several different depths for each attribute. We find that prediction of age and emotion is improved by fine-tuning from earlier layers onward, presumably because deeper layers are progressively invariant to non-identity related changes in the input.

##### Abstract (translated by Google)
我们训练一个深度卷积神经网络，使用一个新的年龄，性别，种族和情感标签注释的公众人物数据集进行身份分类，然后微调属性分类。这个网络中计算资源的最佳共享模式是由实验决定的，只需要1 G的触发器来产生所有的预测。在身份网络的倒数第二层之后的一个附加层中重新学习权重而不是微调，我们为每个属性尝试几个不同的深度。我们发现，通过从前面的层面向前进行微调，可以提高年龄和情绪的预测，这大概是因为更深的层次对于输入中与非身份相关的变化是逐渐不变的。

##### URL
[https://arxiv.org/abs/1609.09018](https://arxiv.org/abs/1609.09018)

##### PDF
[https://arxiv.org/pdf/1609.09018](https://arxiv.org/pdf/1609.09018)

