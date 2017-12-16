---
layout: post
title: "Zero-shot Learning via Shared-Reconstruction-Graph Pursuit"
date: 2017-11-20 13:31:16
categories: arXiv_CV
tags: arXiv_CV Knowledge Embedding
author: Bo Zhao, Xinwei Sun, Yuan Yao, Yizhou Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Zero-shot learning (ZSL) aims to recognize objects from novel unseen classes without any training data. Recently, structure-transfer based methods are proposed to implement ZSL by transferring structural knowledge from the semantic embedding space to image feature space to classify testing images. However, we observe that such a knowledge transfer framework may suffer from the problem of the geometric inconsistency between the data in the training and testing spaces. We call this problem as the space shift problem. In this paper, we propose a novel graph based method to alleviate this space shift problem. Specifically, a Shared Reconstruction Graph (SRG) is pursued to capture the common structure of data in the two spaces. With the learned SRG, each unseen class prototype (cluster center) in the image feature space can be synthesized by the linear combination of other class prototypes, so that testing instances can be classified based on the distance to these synthesized prototypes. The SRG bridges the image feature space and semantic embedding space. By applying spectral clustering on the learned SRG, many meaningful clusters can be discovered, which interprets ZSL performance on the datasets. Our method can be easily extended to the generalized zero-shot learning setting. Experiments on three popular datasets show that our method outperforms other methods on all datasets. Even with a small number of training samples, our method can achieve the state-of-the-art performance.

##### Abstract (translated by Google)
零点学习（ZSL）旨在识别新的看不见的类别的对象，而不需要任何训练数据。最近，基于结构转移的方法被提出来实现ZSL通过结构知识从语义嵌入空间转移到图像特征空间分类测试图像。然而，我们观察到，这样的知识转移框架可能会遭受训练和测试空间中的数据之间的几何不一致的问题。我们把这个问题称为空间转换问题。在本文中，我们提出了一种新的基于图的方法来缓解这个空间转移问题。具体而言，共享重建图（SRG）被用于捕获两个空间中的共同数据结构。通过学习的SRG，图像特征空间中的每个看不见的类原型（聚类中心）都可以通过其他类原型的线性组合来合成，从而可以根据这些合成原型的距离对测试实例进行分类。 SRG桥接图像特征空间和语义嵌入空间。通过在学习的SRG上应用谱聚类，可以发现许多有意义的聚类，从而解释数据集上的ZSL性能。我们的方法可以很容易地扩展到广义的零点学习设置。在三个流行的数据集上的实验表明，我们的方法胜过所有数据集上的其他方法。即使只有少量的训练样本，我们的方法也可以达到最先进的性能。

##### URL
[https://arxiv.org/abs/1711.07302](https://arxiv.org/abs/1711.07302)

##### PDF
[https://arxiv.org/pdf/1711.07302](https://arxiv.org/pdf/1711.07302)

