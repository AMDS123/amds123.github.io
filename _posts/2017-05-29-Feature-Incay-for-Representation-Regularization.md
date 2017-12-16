---
layout: post
title: "Feature Incay for Representation Regularization"
date: 2017-05-29 16:33:54
categories: arXiv_CV
tags: arXiv_CV Regularization Represenation_Learning Classification Deep_Learning
author: Yuhui Yuan, Kuiyuan Yang, Chao Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Softmax loss is widely used in deep neural networks for multi-class classification, where each class is represented by a weight vector, a sample is represented as a feature vector, and the feature vector has the largest projection on the weight vector of the correct category when the model correctly classifies a sample. To ensure generalization, weight decay that shrinks the weight norm is often used as regularizer. Different from traditional learning algorithms where features are fixed and only weights are tunable, features are also tunable as representation learning in deep learning. Thus, we propose feature incay to also regularize representation learning, which favors feature vectors with large norm when the samples can be correctly classified. With the feature incay, feature vectors are further pushed away from the origin along the direction of their corresponding weight vectors, which achieves better inter-class separability. In addition, the proposed feature incay encourages intra-class compactness along the directions of weight vectors by increasing the small feature norm faster than the large ones. Empirical results on MNIST, CIFAR10 and CIFAR100 demonstrate feature incay can improve the generalization ability.

##### Abstract (translated by Google)
Softmax损失广泛应用于多类分类的深度神经网络，其中每个类由一个权向量表示，一个样本表示为一个特征向量，并且该特征向量在正确类别的权向量上具有最大的投影当模型正确分类样本时。为了确保一般化，缩小体重标准的体重衰减通常用作正规化剂。与传统的学习算法不同，在传统的学习算法中，特征是固定的，只有权值是可调的，特征也可以作为深度学习中的表示学习。因此，我们提出了表征学习的规范化方法，当样本可以被正确分类时，它有利于大规范的特征向量。随着特征的变化，特征向量沿着它们相应的权重向量的方向被进一步推离，从而达到更好的类间可分性。此外，所提出的特征提取方法通过增加小规模规范比大规模规范更快来促进沿着权向量方向的类内紧致性。 MNIST，CIFAR10和CIFAR100的实证结果表明，特征提取能够提高泛化能力。

##### URL
[https://arxiv.org/abs/1705.10284](https://arxiv.org/abs/1705.10284)

##### PDF
[https://arxiv.org/pdf/1705.10284](https://arxiv.org/pdf/1705.10284)

