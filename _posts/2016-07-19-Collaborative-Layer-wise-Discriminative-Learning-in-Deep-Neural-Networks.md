---
layout: post
title: "Collaborative Layer-wise Discriminative Learning in Deep Neural Networks"
date: 2016-07-19 07:56:37
categories: arXiv_CV
tags: arXiv_CV Classification Relation
author: Xiaojie Jin, Yunpeng Chen, Jian Dong, Jiashi Feng, Shuicheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
Intermediate features at different layers of a deep neural network are known to be discriminative for visual patterns of different complexities. However, most existing works ignore such cross-layer heterogeneities when classifying samples of different complexities. For example, if a training sample has already been correctly classified at a specific layer with high confidence, we argue that it is unnecessary to enforce rest layers to classify this sample correctly and a better strategy is to encourage those layers to focus on other samples. In this paper, we propose a layer-wise discriminative learning method to enhance the discriminative capability of a deep network by allowing its layers to work collaboratively for classification. Towards this target, we introduce multiple classifiers on top of multiple layers. Each classifier not only tries to correctly classify the features from its input layer, but also coordinates with other classifiers to jointly maximize the final classification performance. Guided by the other companion classifiers, each classifier learns to concentrate on certain training examples and boosts the overall performance. Allowing for end-to-end training, our method can be conveniently embedded into state-of-the-art deep networks. Experiments with multiple popular deep networks, including Network in Network, GoogLeNet and VGGNet, on scale-various object classification benchmarks, including CIFAR100, MNIST and ImageNet, and scene classification benchmarks, including MIT67, SUN397 and Places205, demonstrate the effectiveness of our method. In addition, we also analyze the relationship between the proposed method and classical conditional random fields models.

##### Abstract (translated by Google)
已知深层神经网络的不同层的中间特征对不同复杂度的视觉模式具有区别性。然而，大多数现有的工作在对不同复杂度的样本进行分类时忽略了这种跨层异质性。例如，如果一个训练样本已经被高度置信地正确地分类在一个特定的层次上，我们认为没有必要强制休息层来对这个样本进行正确分类，更好的策略是鼓励这些层次关注其他样本。在本文中，我们提出了一种分层的判别式学习方法，通过允许其层次进行协同分类来提高深层网络的判别能力。为了实现这个目标，我们在多个图层上引入了多个分类器。每个分类器不仅试图从其输入层正确分类特征，而且还与其他分类器协调以共同最大化分类性能。在其他同伴分类器的引导下，每个分类器学习集中在某些训练样例上，提高整体性能。考虑到端到端的培训，我们的方法可以方便地嵌入到最先进的深度网络中。包括网络网络，GoogLeNet和VGGNet在内的多种流行的深度网络实验，包括CIFAR100，MNIST和ImageNet在内的各种对象分类基准以及包括MIT67，SUN397和Places205在内的场景分类基准，证明了我们方法的有效性。另外还分析了该方法与经典条件随机场模型之间的关系。

##### URL
[https://arxiv.org/abs/1607.05440](https://arxiv.org/abs/1607.05440)

##### PDF
[https://arxiv.org/pdf/1607.05440](https://arxiv.org/pdf/1607.05440)

