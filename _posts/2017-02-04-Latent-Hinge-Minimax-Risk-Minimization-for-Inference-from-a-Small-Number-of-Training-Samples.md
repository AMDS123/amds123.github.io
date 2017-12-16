---
layout: post
title: "Latent Hinge-Minimax Risk Minimization for Inference from a Small Number of Training Samples"
date: 2017-02-04 14:33:16
categories: arXiv_CV
tags: arXiv_CV Transfer_Learning Inference Deep_Learning
author: Dolev Raviv, Margarita Osadchy
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Learning (DL) methods show very good performance when trained on large, balanced data sets. However, many practical problems involve imbalanced data sets, or/and classes with a small number of training samples. The performance of DL methods as well as more traditional classifiers drops significantly in such settings. Most of the existing solutions for imbalanced problems focus on customizing the data for training. A more principled solution is to use mixed Hinge-Minimax risk [19] specifically designed to solve binary problems with imbalanced training sets. Here we propose a Latent Hinge Minimax (LHM) risk and a training algorithm that generalizes this paradigm to an ensemble of hyperplanes that can form arbitrary complex, piecewise linear boundaries. To extract good features, we combine LHM model with CNN via transfer learning. To solve multi-class problem we map pre-trained category-specific LHM classifiers to a multi-class neural network and adjust the weights with very fast tuning. LHM classifier enables the use of unlabeled data in its training and the mapping allows for multi-class inference, resulting in a classifier that performs better than alternatives when trained on a small number of training samples.

##### Abstract (translated by Google)
深度学习（DL）方法在大型平衡数据集上训练时表现出非常好的性能。然而，许多实际问题涉及不平衡的数据集，或/和具有少量训练样本的类。 DL方法以及更传统的分类器的性能在这样的设置下显着下降。解决不平衡问题的现有解决方案大多集中在为培训定制数据。一个更原则的解决方案是使用专门设计用于解决不平衡训练集合的二元问题的混合的Hinge-Minimax风险[19]。在这里，我们提出了一个潜在铰链极小极小（LHM）风险和一个训练算法，将这个范例推广到一个超平面集合，它可以形成任意复杂的分段线性边界。为了提取良好的特征，我们通过转移学习将LHM模型与CNN相结合。为了解决多类问题，我们将预先训练的类别特定的LHM分类器映射到多类神经网络，并通过非常快的调整来调整权重。 LHM分类器允许在其训练中使用未标记的数据，并且映射允许多类别推断，从而导致分类器在少量训练样本上训练时表现比替代方案更好。

##### URL
[https://arxiv.org/abs/1702.01293](https://arxiv.org/abs/1702.01293)

##### PDF
[https://arxiv.org/pdf/1702.01293](https://arxiv.org/pdf/1702.01293)

