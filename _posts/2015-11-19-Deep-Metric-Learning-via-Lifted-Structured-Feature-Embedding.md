---
layout: post
title: "Deep Metric Learning via Lifted Structured Feature Embedding"
date: 2015-11-19 23:41:11
categories: arXiv_CV
tags: arXiv_CV Embedding CNN Prediction Recognition
author: Hyun Oh Song, Yu Xiang, Stefanie Jegelka, Silvio Savarese
mathjax: true
---

* content
{:toc}

##### Abstract
Learning the distance metric between pairs of examples is of great importance for learning and visual recognition. With the remarkable success from the state of the art convolutional neural networks, recent works have shown promising results on discriminatively training the networks to learn semantic feature embeddings where similar examples are mapped close to each other and dissimilar examples are mapped farther apart. In this paper, we describe an algorithm for taking full advantage of the training batches in the neural network training by lifting the vector of pairwise distances within the batch to the matrix of pairwise distances. This step enables the algorithm to learn the state of the art feature embedding by optimizing a novel structured prediction objective on the lifted problem. Additionally, we collected Online Products dataset: 120k images of 23k classes of online products for metric learning. Our experiments on the CUB-200-2011, CARS196, and Online Products datasets demonstrate significant improvement over existing deep feature embedding methods on all experimented embedding sizes with the GoogLeNet network.

##### Abstract (translated by Google)
学习示例对之间的距离度量对学习和视觉识别非常重要。由于现有技术的卷积神经网络的显着成功，最近的工作已经显示出有前途的结果，用于对网络进行有差别的训练以学习语义特征嵌入，其中类似的例子被映射得彼此接近，不相似的例子被映射得更远。在本文中，我们描述了一种充分利用训练批次在神经网络训练中的算法，通过将批次内的成对距离的向量提升到成对距离的矩阵。这个步骤使算法能够通过优化关于解除的问题的新颖的结构化预测目标来学习最先进的特征嵌入的状态。此外，我们收集了Online Products数据集：用于度量学习的23k类在线产品的120k图像。我们在CUB-200-2011，CARS196和Online Products数据集上进行的实验证明，与使用GoogLeNet网络的所有实验嵌入大小相比，现有的深度特征嵌入方法有显着的改进。

##### URL
[https://arxiv.org/abs/1511.06452](https://arxiv.org/abs/1511.06452)

##### PDF
[https://arxiv.org/pdf/1511.06452](https://arxiv.org/pdf/1511.06452)

