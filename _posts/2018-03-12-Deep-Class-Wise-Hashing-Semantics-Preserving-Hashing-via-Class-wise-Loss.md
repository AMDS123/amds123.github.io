---
layout: post
title: "Deep Class-Wise Hashing: Semantics-Preserving Hashing via Class-wise Loss"
date: 2018-03-12 07:19:04
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Embedding CNN Optimization Deep_Learning
author: Xuefei Zhe, Shifeng Chen, Hong Yan
mathjax: true
---

* content
{:toc}

##### Abstract
Deep supervised hashing has emerged as an influential solution to large-scale semantic image retrieval problems in computer vision. In the light of recent progress, convolutional neural network based hashing methods typically seek pair-wise or triplet labels to conduct the similarity preserving learning. However, complex semantic concepts of visual contents are hard to capture by similar/dissimilar labels, which limits the retrieval performance. Generally, pair-wise or triplet losses not only suffer from expensive training costs but also lack in extracting sufficient semantic information. In this regard, we propose a novel deep supervised hashing model to learn more compact class-level similarity preserving binary codes. Our deep learning based model is motivated by deep metric learning that directly takes semantic labels as supervised information in training and generates corresponding discriminant hashing code. Specifically, a novel cubic constraint loss function based on Gaussian distribution is proposed, which preserves semantic variations while penalizes the overlap part of different classes in the embedding space. To address the discrete optimization problem introduced by binary codes, a two-step optimization strategy is proposed to provide efficient training and avoid the problem of gradient vanishing. Extensive experiments on four large-scale benchmark databases show that our model can achieve the state-of-the-art retrieval performance. Moreover, when training samples are limited, our method surpasses other supervised deep hashing methods with non-negligible margins.

##### Abstract (translated by Google)
深度监督哈希已经成为解决计算机视觉中大规模语义图像检索问题的有效方法。鉴于最近的进展，基于卷积神经网络的哈希方法通常寻求成对或三重标签来进行相似性保持学习。然而，视觉内容的复杂语义概念很难被相似/不相似的标签捕获，这限制了检索性能。一般来说，成对或三重损失不仅要承担昂贵的培训成本，而且缺乏提取足够的语义信息。在这方面，我们提出了一种新的深度监督哈希模型来学习更紧凑的类级保持二进制码。我们的深度学习模型是由深度度量学习推动的，它直接将语义标签作为训练中的监督信息并生成相应的判别式散列码。具体而言，提出了一种新的基于高斯分布的三次约束损失函数，该函数保留了语义变异，同时惩罚了嵌入空间中不同类别的重叠部分。为解决二进制编码引入的离散优化问题，提出了两步优化策略，以提供有效的训练并避免梯度消失的问题。在四个大型基准数据库上进行的大量实验表明，我们的模型可以实现最先进的检索性能。而且，当训练样本数量有限时，我们的方法超过了其他受监督的深度散列方法，并且边界不可忽略。

##### URL
[https://arxiv.org/abs/1803.04137](https://arxiv.org/abs/1803.04137)

##### PDF
[https://arxiv.org/pdf/1803.04137](https://arxiv.org/pdf/1803.04137)

