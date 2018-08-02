---
layout: post
title: "A Network Structure to Explicitly Reduce Confusion Errors in Semantic Segmentation"
date: 2018-08-01 13:37:59
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge Segmentation Semantic_Segmentation Classification Deep_Learning Detection
author: Qichuan Geng, Xinyu Huang, Zhong Zhou, Ruigang Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Confusing classes that are ubiquitous in real world often degrade performance for many vision related applications like object detection, classification, and segmentation. The confusion errors are not only caused by similar visual patterns but also amplified by various factors during the training of our designed models, such as reduced feature resolution in the encoding process or imbalanced data distributions. A large amount of deep learning based network structures has been proposed in recent years to deal with these individual factors and improve network performance. However, to our knowledge, no existing work in semantic image segmentation is designed to tackle confusion errors explicitly. In this paper, we present a novel and general network structure that reduces confusion errors in more direct manner and apply the network for semantic segmentation. There are two major contributions in our network structure: 1) We ensemble subnets with heterogeneous output spaces based on the discriminative confusing groups. The training for each subnet can distinguish confusing classes within the group without affecting unrelated classes outside the group. 2) We propose an improved cross-entropy loss function that maximizes the probability assigned to the correct class and penalizes the probabilities assigned to the confusing classes at the same time. Our network structure is a general structure and can be easily adapted to any other networks to further reduce confusion errors. Without any changes in the feature encoder and post-processing steps, our experiments demonstrate consistent and significant improvements on different baseline models on Cityscapes and PASCAL VOC datasets (e.g., 3.05% over ResNet-101 and 1.30% over ResNet-38).

##### Abstract (translated by Google)
在现实世界中普遍存在的令人困惑的类通常会降低许多与视觉相关的应用程序（如对象检测，分类和分段）的性能。混淆错误不仅由类似的视觉模式引起，而且在我们设计的模型训练期间也被各种因素放大，例如编码过程中的特征分辨率降低或数据分布不均衡。近年来，已经提出了大量基于深度学习的网络结构来处理这些个体因素并改善网络性能。然而，据我们所知，语义图像分割中的任何现有工作都没有被设计用于明确地解决混淆错误。在本文中，我们提出了一种新颖的通用网络结构，以更直接的方式减少混淆错误，并将网络应用于语义分割。我们的网络结构有两个主要的贡献：1）我们根据有区别的混淆组合成具有异构输出空间的子网。每个子网的培训可以区分组内的混淆类，而不会影响组外的不相关类。 2）我们提出了一种改进的交叉熵损失函数，该函数最大化分配给正确类的概率，并同时惩罚分配给混淆类的概率。我们的网络结构是一般结构，可以很容易地适应任何其他网络，以进一步减少混淆错误。在没有对特征编码器和后处理步骤进行任何更改的情况下，我们的实验证明了Cityscapes和PASCAL VOC数据集上不同基线模型的一致且显着的改进（例如，ResNet-101为3.05％，ResNet-38为1.30％）。

##### URL
[https://arxiv.org/abs/1808.00313](https://arxiv.org/abs/1808.00313)

##### PDF
[https://arxiv.org/pdf/1808.00313](https://arxiv.org/pdf/1808.00313)

