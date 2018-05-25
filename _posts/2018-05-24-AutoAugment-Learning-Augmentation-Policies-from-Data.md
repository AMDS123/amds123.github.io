---
layout: post
title: "AutoAugment: Learning Augmentation Policies from Data"
date: 2018-05-24 04:05:42
categories: arXiv_CV
tags: arXiv_CV Classification
author: Ekin D. Cubuk, Barret Zoph, Dandelion Mane, Vijay Vasudevan, Quoc V. Le
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we take a closer look at data augmentation for images, and describe a simple procedure called AutoAugment to search for improved data augmentation policies. Our key insight is to create a search space of data augmentation policies, evaluating the quality of a particular policy directly on the dataset of interest. In our implementation, we have designed a search space where a policy consists of many sub-policies, one of which is randomly chosen for each image in each mini-batch. A sub-policy consists of two operations, each operation being an image processing function such as translation, rotation, or shearing, and the probabilities and magnitudes with which the functions are applied. We use a search algorithm to find the best policy such that the neural network yields the highest validation accuracy on a target dataset. Our method achieves state-of-the-art accuracy on CIFAR-10, CIFAR-100, SVHN, and ImageNet (without additional data). On ImageNet, we attain a Top-1 accuracy of 83.54%. On CIFAR-10, we achieve an error rate of 1.48%, which is 0.65% better than the previous state-of-the-art. On reduced data settings, AutoAugment performs comparably to semi-supervised methods without using any unlabeled examples. Finally, policies learned from one dataset can be transferred to work well on other similar datasets. For example, the policy learned on ImageNet allows us to achieve state-of-the-art accuracy on the fine grained visual classification dataset Stanford Cars, without fine-tuning weights pre-trained on additional data.

##### Abstract (translated by Google)
在本文中，我们仔细研究图像的数据增强，并描述一个名为AutoAugment的简单过程，以搜索改进的数据增强策略。我们的主要见解是创建数据增强策略的搜索空间，直接针对感兴趣的数据集评估特定策略的质量。在我们的实施中，我们设计了一个搜索空间，其中一个策略由许多子策略组成，其中一个随机选择每个小批量中的每个图像。子策略由两个操作组成，每个操作都是图像处理功能，如平移，旋转或剪切，以及应用这些功能的概率和大小。我们使用搜索算法来找到最佳策略，以使神经网络在目标数据集上获得最高的验证准确度。我们的方法在CIFAR-10，CIFAR-100，SVHN和ImageNet上实现了最新的准确性（无需额外的数据）。在ImageNet上，我们获得83.54％的Top-1精度。在CIFAR-10上，我们实现了1.48％的错误率，比先前的先进水平好0.65％。在减少数据设置的情况下，AutoAugment与半监督方法相比可以执行同样的操作，而无需使用任何未标记的示例。最后，从一个数据集中学习的政策可以转移到其他类似数据集上运行良好。例如，在ImageNet上学习的政策使我们能够在精细粒度的视觉分类数据集斯坦福汽车中实现最新的精确度，而无需对预先训练过的其他数据进行微调。

##### URL
[http://arxiv.org/abs/1805.09501](http://arxiv.org/abs/1805.09501)

##### PDF
[http://arxiv.org/pdf/1805.09501](http://arxiv.org/pdf/1805.09501)

