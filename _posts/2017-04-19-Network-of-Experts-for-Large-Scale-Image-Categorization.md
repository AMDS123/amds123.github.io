---
layout: post
title: "Network of Experts for Large-Scale Image Categorization"
date: 2017-04-19 16:25:14
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Image_Classification Classification
author: Karim Ahmed, Mohammad Haris Baig, Lorenzo Torresani
mathjax: true
---

* content
{:toc}

##### Abstract
We present a tree-structured network architecture for large scale image classification. The trunk of the network contains convolutional layers optimized over all classes. At a given depth, the trunk splits into separate branches, each dedicated to discriminate a different subset of classes. Each branch acts as an expert classifying a set of categories that are difficult to tell apart, while the trunk provides common knowledge to all experts in the form of shared features. The training of our "network of experts" is completely end-to-end: the partition of categories into disjoint subsets is learned simultaneously with the parameters of the network trunk and the experts are trained jointly by minimizing a single learning objective over all classes. The proposed structure can be built from any existing convolutional neural network (CNN). We demonstrate its generality by adapting 4 popular CNNs for image categorization into the form of networks of experts. Our experiments on CIFAR100 and ImageNet show that in every case our method yields a substantial improvement in accuracy over the base CNN, and gives the best result achieved so far on CIFAR100. Finally, the improvement in accuracy comes at little additional cost: compared to the base network, the training time is only moderately increased and the number of parameters is comparable or in some cases even lower.

##### Abstract (translated by Google)
我们提出了一个用于大规模图像分类的树状结构网络体系结构。网络的主干包含对所有类进行优化的卷积层。在一个给定的深度，干线分成不同的分支，每个分支专用于区分不同类别的子集。每个分支都作为一个专家分类一组难以区分的类别，而主干以共享特征的形式向所有专家提供常识。我们的“专家网络”的培训是完全端对端的：将类别划分为不相交的子集与网络中继线的参数同时学习，并且通过最小化所有类别的单个学习目标来共同训练专家。所提出的结构可以从任何现有的卷积神经网络（CNN）构建。我们通过将4种流行的CNN图像分类适应专家网络的形式来证明其一般性。我们在CIFAR100和ImageNet上进行的实验表明，在每一种情况下，我们的方法都比基本的CNN在精度上有显着的提高，并且在CIFAR100上取得了最好的结果。最后，精度的提高带来了额外的成本：与基础网络相比，训练时间只是适度增加，参数的数量是可比较的，有些甚至更低。

##### URL
[https://arxiv.org/abs/1604.06119](https://arxiv.org/abs/1604.06119)

##### PDF
[https://arxiv.org/pdf/1604.06119](https://arxiv.org/pdf/1604.06119)

