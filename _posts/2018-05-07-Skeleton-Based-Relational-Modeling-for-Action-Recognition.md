---
layout: post
title: "Skeleton-Based Relational Modeling for Action Recognition"
date: 2018-05-07 14:59:54
categories: arXiv_CV
tags: arXiv_CV Attention Action_Recognition CNN RNN Relation Recognition
author: Lin Li, Wu Zheng, Zhaoxiang Zhang, Yan Huang, Liang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
With the fast development of effective and low-cost human skeleton capture systems, skeleton-based action recognition has attracted much attention recently. Most existing methods use Convolutional Neural Network(CNN) and Recurrent Neural Network(RNN) to extract spatio-temporal information embedded in the skeleton sequences for action recognition. However, these approaches are limited in the ability of relational modeling in a single skeleton, due to the loss of important structural information when converting the raw skeleton data to adapt to the CNN or RNN input. In this paper, we propose an Attentional Recurrent Relational Network-LSTM(ARRN-LSTM) to simultaneously model spatial configurations and temporal dynamics in skeletons for action recognition. The spatial patterns embedded in a single skeleton are learned by a Recurrent Relational Network, followed by a multi-layer LSTM to extract temporal features in the skeleton sequences. To exploit the complementarity between different geometries in the skeleton for sufficient relational modeling, we design a two-stream architecture to learn the relationship among joints and explore the underlying patterns among lines simultaneously. We also introduce an adaptive attentional module for focusing on potential discriminative parts of the skeleton towards a certain action. Extensive experiments are performed on several popular action recognition datasets and the results show that the proposed approach achieves competitive results with the state-of-the-art methods.

##### Abstract (translated by Google)
随着有效和低成本的人体骨骼捕获系统的快速发展，基于骨骼的动作识别近来备受关注。现有的大多数方法都是使用卷积神经网络（CNN）和递归神经网络（RNN）来提取嵌入骨架序列中的时空信息进行动作识别。然而，由于在转换原始骨架数据以适应CNN或RNN输入时丢失重要的结构信息，这些方法在单个骨架中的关系建模能力方面受到限制。在本文中，我们提出了一个注意循环关系网络LSTM（ARRN-LSTM），用于同时为动作识别的骨架中的空间配置和时间动态建模。嵌入在单个骨架中的空间模式通过循环关系网络学习，然后是多层LSTM以提取骨架序列中的时间特征。为了利用骨架中不同几何之间的互补性来进行充分的关系建模，我们设计了一个双流体系结构来学习关节之间的关系，并同时探索行间的底层模式。我们还引入了一个适应性注意模块，用于将焦点放在骨骼的潜在区分部分上，以适应特定的动作。对几种流行的动作识别数据集进行了广泛的实验，结果表明，所提出的方法通过最先进的方法实现了竞争结果。

##### URL
[http://arxiv.org/abs/1805.02556](http://arxiv.org/abs/1805.02556)

##### PDF
[http://arxiv.org/pdf/1805.02556](http://arxiv.org/pdf/1805.02556)

