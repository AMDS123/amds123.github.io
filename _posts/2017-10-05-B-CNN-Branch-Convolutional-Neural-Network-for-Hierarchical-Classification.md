---
layout: post
title: "B-CNN: Branch Convolutional Neural Network for Hierarchical Classification"
date: 2017-10-05 08:14:57
categories: arXiv_CV
tags: arXiv_CV Knowledge GAN CNN Classification Prediction
author: Xinqi Zhu, Michael Bain
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Network (CNN) image classifiers are traditionally designed to have sequential convolutional layers with a single output layer. This is based on the assumption that all target classes should be treated equally and exclusively. However, some classes can be more difficult to distinguish than others, and classes may be organized in a hierarchy of categories. At the same time, a CNN is designed to learn internal representations that abstract from the input data based on its hierarchical layered structure. So it is natural to ask if an inverse of this idea can be applied to learn a model that can predict over a classification hierarchy using multiple output layers in decreasing order of class abstraction. In this paper, we introduce a variant of the traditional CNN model named the Branch Convolutional Neural Network (B-CNN). A B-CNN model outputs multiple predictions ordered from coarse to fine along the concatenated convolutional layers corresponding to the hierarchical structure of the target classes, which can be regarded as a form of prior knowledge on the output. To learn with B-CNNs a novel training strategy, named the Branch Training strategy (BT-strategy), is introduced which balances the strictness of the prior with the freedom to adjust parameters on the output layers to minimize the loss. In this way we show that CNN based models can be forced to learn successively coarse to fine concepts in the internal layers at the output stage, and that hierarchical prior knowledge can be adopted to boost CNN models' classification performance. Our models are evaluated to show that the B-CNN extensions improve over the corresponding baseline CNN on the benchmark datasets MNIST, CIFAR-10 and CIFAR-100.

##### Abstract (translated by Google)
卷积神经网络（CNN）图像分类器传统上被设计为具有单一输出层的顺序卷积层。这是基于所有目标类别应该被平等和专门对待的假设。然而，有些课程可能比其他课程更难以区分，而课程可能按类别层次结构组织。与此同时，CNN被设计用来学习从输入数据中抽象出来的内部表示。所以很自然地问，这个思想的逆过程是否可以用来学习一个模型，该模型可以按照类抽象的递减顺序使用多个输出层来预测分类层次结构。在本文中，我们介绍一种名为分支卷积神经网络（B-CNN）的传统CNN模型的变体。 B-CNN模型输出对应于目标类的层次结构的连续卷积层从粗到细排序的多个预测，这可以被认为是对输出的先验知识的一种形式。为了学习B-CNN，引入了一种名为分支训练战略（BT-strategy）的新型训练策略，其平衡了先前的严格性和在输出层上调整参数的自由度以使损失最小化。通过这种方式，我们可以证明基于CNN的模型可以被迫在输出阶段的内层逐步学习粗到细的概念，并且可以采用层次先验知识来提升CNN模型的分类性能。我们的模型进行评估，以显示B-CNN扩展在基准数据集MNIST，CIFAR-10和CIFAR-100上的相应基线CNN上改善。

##### URL
[https://arxiv.org/abs/1709.09890](https://arxiv.org/abs/1709.09890)

##### PDF
[https://arxiv.org/pdf/1709.09890](https://arxiv.org/pdf/1709.09890)

