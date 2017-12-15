---
layout: post
title: "Learning Discriminative Features with Class Encoder"
date: 2016-05-09 06:04:14
categories: arXiv_CV
tags: arXiv_CV Face Classification Recognition Face_Recognition
author: Hailin Shi, Xiangyu Zhu, Zhen Lei, Shengcai Liao, Stan Z. Li
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks usually benefit from unsupervised pre-training, e.g. auto-encoders. However, the classifier further needs supervised fine-tuning methods for good discrimination. Besides, due to the limits of full-connection, the application of auto-encoders is usually limited to small, well aligned images. In this paper, we incorporate the supervised information to propose a novel formulation, namely class-encoder, whose training objective is to reconstruct a sample from another one of which the labels are identical. Class-encoder aims to minimize the intra-class variations in the feature space, and to learn a good discriminative manifolds on a class scale. We impose the class-encoder as a constraint into the softmax for better supervised training, and extend the reconstruction on feature-level to tackle the parameter size issue and translation issue. The experiments show that the class-encoder helps to improve the performance on benchmarks of classification and face recognition. This could also be a promising direction for fast training of face recognition models.

##### Abstract (translated by Google)
深度神经网络通常受益于无监督的预训练，例如，自动编码器。然而，分类器还需要有监督的微调方法来进行良好的判别。此外，由于全连接的限制，自动编码器的应用通常局限于小的，良好对齐的图像。在本文中，我们引入了监督信息来提出一个新的公式，即类编码器，其训练目标是从另一个标签重新构造一个样本。类编码器旨在最大限度地减少特征空间中的类内变化，并在班级上学习良好的歧视流形。为了更好的监督训练，我们将类编码器作为约束条件加入到softmax中，并且扩展特征级的重构以解决参数尺寸问题和翻译问题。实验表明，类编码器有助于提高分类和人脸识别基准的性能。这对于人脸识别模型的快速培训也是一个有前途的方向。

##### URL
[https://arxiv.org/abs/1605.02424](https://arxiv.org/abs/1605.02424)

##### PDF
[https://arxiv.org/pdf/1605.02424](https://arxiv.org/pdf/1605.02424)

