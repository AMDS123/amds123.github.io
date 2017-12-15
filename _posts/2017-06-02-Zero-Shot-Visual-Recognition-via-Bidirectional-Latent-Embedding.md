---
layout: post
title: "Zero-Shot Visual Recognition via Bidirectional Latent Embedding"
date: 2017-06-02 17:18:27
categories: arXiv_CV
tags: arXiv_CV Knowledge Attention Action_Recognition Embedding Recognition
author: Qian Wang, Ke Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Zero-shot learning for visual recognition, e.g., object and action recognition, has recently attracted a lot of attention. However, it still remains challenging in bridging the semantic gap between visual features and their underlying semantics and transferring knowledge to semantic categories unseen during learning. Unlike most of the existing zero-shot visual recognition methods, we propose a stagewise bidirectional latent embedding framework to two subsequent learning stages for zero-shot visual recognition. In the bottom-up stage, a latent embedding space is first created by exploring the topological and labeling information underlying training data of known classes via a proper supervised subspace learning algorithm and the latent embedding of training data are used to form landmarks that guide embedding semantics underlying unseen classes into this learned latent space. In the top-down stage, semantic representations of unseen-class labels in a given label vocabulary are then embedded to the same latent space to preserve the semantic relatedness between all different classes via our proposed semi-supervised Sammon mapping with the guidance of landmarks. Thus, the resultant latent embedding space allows for predicting the label of a test instance with a simple nearest-neighbor rule. To evaluate the effectiveness of the proposed framework, we have conducted extensive experiments on four benchmark datasets in object and action recognition, i.e., AwA, CUB-200-2011, UCF101 and HMDB51. The experimental results under comparative studies demonstrate that our proposed approach yields the state-of-the-art performance under inductive and transductive settings.

##### Abstract (translated by Google)
视觉识别的零点学习，例如对象和动作识别，近来引起了很多关注。然而，在弥合视觉特征与其底层语义之间的语义鸿沟，并将知识转化为学习过程中看不到的语义类别方面仍然具有挑战性。与大多数现有的零镜头视觉识别方法不同，我们提出了一个分阶段的双向潜在嵌入框架，以后续的两个学习阶段为零镜头视觉识别。在自下而上的阶段，首先通过适当的监督子空间学习算法，探索已知类别的训练数据下的拓扑和标记信息，并利用训练数据的潜在嵌入形成引导嵌入语义的界标，从而形成潜在的嵌入空间根本看不见的类进入这个学习的潜在空间。在自上而下的阶段，通过我们提出的半监督Sammon映射，在地标的引导下，将给定标签词汇中的未知类标签的语义表示嵌入到相同的潜在空间，以保持所有不同类之间的语义相关性。因此，所得到的潜在嵌入空间允许用简单的最近邻居规则来预测测试实例的标签。为了评估所提出的框架的有效性，我们已经在对象和动作识别的四个基准数据集（即AwA，CUB-200-2011，UCF101和HMDB51）上进行了广泛的实验。在比较研究下的实验结果表明，我们提出的方法在感应和换能设置下获得了最先进的性能。

##### URL
[https://arxiv.org/abs/1607.02104](https://arxiv.org/abs/1607.02104)

##### PDF
[https://arxiv.org/pdf/1607.02104](https://arxiv.org/pdf/1607.02104)

