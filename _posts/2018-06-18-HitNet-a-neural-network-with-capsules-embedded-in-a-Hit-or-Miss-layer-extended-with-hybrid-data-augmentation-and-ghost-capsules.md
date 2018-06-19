---
layout: post
title: "HitNet: a neural network with capsules embedded in a Hit-or-Miss layer, extended with hybrid data augmentation and ghost capsules"
date: 2018-06-18 07:08:11
categories: arXiv_AI
tags: arXiv_AI Classification
author: Adrien Deli&#xe8;ge, Anthony Cioppa, Marc Van Droogenbroeck
mathjax: true
---

* content
{:toc}

##### Abstract
Neural networks designed for the task of classification have become a commodity in recent years. Many works target the development of better networks, which results in a complexification of their architectures with more layers, multiple sub-networks, or even the combination of multiple classifiers. In this paper, we show how to redesign a simple network to reach excellent performances, which are better than the results reproduced with CapsNet on several datasets, by replacing a layer with a Hit-or-Miss layer. This layer contains activated vectors, called capsules, that we train to hit or miss a central capsule by tailoring a specific centripetal loss function. We also show how our network, named HitNet, is capable of synthesizing a representative sample of the images of a given class by including a reconstruction network. This possibility allows to develop a data augmentation step combining information from the data space and the feature space, resulting in a hybrid data augmentation process. In addition, we introduce the possibility for HitNet, to adopt an alternative to the true target when needed by using the new concept of ghost capsules, which is used here to detect potentially mislabeled images in the training data.

##### Abstract (translated by Google)
为分类任务设计的神经网络近年来已成为一种商品。许多作品的目标是开发更好的网络，导致其架构与更多层，多个子网或甚至多个分类器的组合的复杂化。在本文中，我们展示了如何重新设计一个简单的网络以达到出色的性能，这比通过CapsNet在几个数据集上再现的结果要好，通过用Hit-or-Miss层替换一个图层。该层包含被激活的载体，称为胶囊，通过调整特定的向心丢失函数来训练它们击中或错过中央胶囊。我们还展示了我们的网络HitNet如何能够通过包含重构网络来合成给定类别的图像的代表性样本。这种可能性允许开发数据增加步骤，将来自数据空间和特征空间的信息组合起来，产生混合数据增强处理。此外，我们引入HitNet的可能性，通过使用鬼胶囊的新概念，在需要时采用替代真实目标的方法，这种方法用于检测训练数据中潜在的误标记图像。

##### URL
[http://arxiv.org/abs/1806.06519](http://arxiv.org/abs/1806.06519)

##### PDF
[http://arxiv.org/pdf/1806.06519](http://arxiv.org/pdf/1806.06519)

