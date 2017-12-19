---
layout: post
title: "Sparsifying Neural Network Connections for Face Recognition"
date: 2015-12-07 02:56:27
categories: arXiv_CV
tags: arXiv_CV Sparse Face Relation Recognition Face_Recognition
author: Yi Sun, Xiaogang Wang, Xiaoou Tang
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes to learn high-performance deep ConvNets with sparse neural connections, referred to as sparse ConvNets, for face recognition. The sparse ConvNets are learned in an iterative way, each time one additional layer is sparsified and the entire model is re-trained given the initial weights learned in previous iterations. One important finding is that directly training the sparse ConvNet from scratch failed to find good solutions for face recognition, while using a previously learned denser model to properly initialize a sparser model is critical to continue learning effective features for face recognition. This paper also proposes a new neural correlation-based weight selection criterion and empirically verifies its effectiveness in selecting informative connections from previously learned models in each iteration. When taking a moderately sparse structure (26%-76% of weights in the dense model), the proposed sparse ConvNet model significantly improves the face recognition performance of the previous state-of-the-art DeepID2+ models given the same training data, while it keeps the performance of the baseline model with only 12% of the original parameters.

##### Abstract (translated by Google)
本文提出了学习用于人脸识别的具有稀疏神经连接的高性能深度通信网络（称为稀疏通信网络）。稀疏ConvNets是以迭代的方式学习的，每次一个额外的层被稀疏并且整个模型被重新训练，给定在之前迭代中学习到的初始权重。一个重要的发现是，从头开始直接训练稀疏的ConvNet未能找到好的人脸识别解决方案，而使用以前学过的密度模型正确地初始化稀疏模型对于继续学习人脸识别的有效特征至关重要。本文还提出了一种新的基于神经关联的权重选择标准，并在每次迭代中验证其从先前学习的模型中选择信息连接的有效性。当采用适度稀疏结构（稠密模型中权重的26％-76％）时，所提出的稀疏ConvNet模型在给定相同训练数据的情况下显着提高了以前最先进的DeepID2 +模型的人脸识别性能，而它使基准模型的性能仅保留原始参数的12％。

##### URL
[https://arxiv.org/abs/1512.01891](https://arxiv.org/abs/1512.01891)

##### PDF
[https://arxiv.org/pdf/1512.01891](https://arxiv.org/pdf/1512.01891)

