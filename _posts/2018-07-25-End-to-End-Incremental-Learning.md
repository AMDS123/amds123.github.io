---
layout: post
title: "End-to-End Incremental Learning"
date: 2018-07-25 11:38:25
categories: arXiv_CV
tags: arXiv_CV Knowledge Image_Classification Classification Deep_Learning
author: Francisco M. Castro, Manuel J. Mar&#xed;n-Jim&#xe9;nez, Nicol&#xe1;s Guil, Cordelia Schmid, Karteek Alahari
mathjax: true
---

* content
{:toc}

##### Abstract
Although deep learning approaches have stood out in recent years due to their state-of-the-art results, they continue to suffer from catastrophic forgetting, a dramatic decrease in overall performance when training with new classes added incrementally. This is due to current neural network architectures requiring the entire dataset, consisting of all the samples from the old as well as the new classes, to update the model -a requirement that becomes easily unsustainable as the number of classes grows. We address this issue with our approach to learn deep neural networks incrementally, using new data and only a small exemplar set corresponding to samples from the old classes. This is based on a loss composed of a distillation measure to retain the knowledge acquired from the old classes, and a cross-entropy loss to learn the new classes. Our incremental training is achieved while keeping the entire framework end-to-end, i.e., learning the data representation and the classifier jointly, unlike recent methods with no such guarantees. We evaluate our method extensively on the CIFAR-100 and ImageNet (ILSVRC 2012) image classification datasets, and show state-of-the-art performance.

##### Abstract (translated by Google)
尽管近年来深度学习方法由于其最先进的结果而脱颖而出，但它们仍然遭受灾难性的遗忘，当新课程的培训逐渐增加时，整体表现急剧下降。这是由于当前的神经网络架构需要整个数据集，包括来自旧类和新类的所有样本，以更新模型 - 随着类数量的增加，这一要求变得容易不可持续。我们通过逐步学习深度神经网络的方法来解决这个问题，使用新数据并且只使用与旧类中的样本相对应的小样本集。这是基于由蒸馏措施组成的损失，以保留从旧类中获得的知识，以及用于学习新类的交叉熵损失。我们的增量训练是在保持整个框架端到端的同时实现的，即共同学习数据表示和分类器，不像最近没有这种保证的方法。我们在CIFAR-100和ImageNet（ILSVRC 2012）图像分类数据集上广泛评估我们的方法，并展示最先进的性能。

##### URL
[http://arxiv.org/abs/1807.09536](http://arxiv.org/abs/1807.09536)

##### PDF
[http://arxiv.org/pdf/1807.09536](http://arxiv.org/pdf/1807.09536)

