---
layout: post
title: "MARTA GANs: Unsupervised Representation Learning for Remote Sensing Image Classification"
date: 2017-11-21 07:15:41
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN CNN Image_Classification Represenation_Learning Classification Deep_Learning
author: Daoyu Lin, Kun Fu, Yang Wang, Guangluan Xu, Xian Sun
mathjax: true
---

* content
{:toc}

##### Abstract
With the development of deep learning, supervised learning has frequently been adopted to classify remotely sensed images using convolutional networks (CNNs). However, due to the limited amount of labeled data available, supervised learning is often difficult to carry out. Therefore, we proposed an unsupervised model called multiple-layer feature-matching generative adversarial networks (MARTA GANs) to learn a representation using only unlabeled data. MARTA GANs consists of both a generative model $G$ and a discriminative model $D$. We treat $D$ as a feature extractor. To fit the complex properties of remote sensing data, we use a fusion layer to merge the mid-level and global features. $G$ can produce numerous images that are similar to the training data; therefore, $D$ can learn better representations of remotely sensed images using the training data provided by $G$. The classification results on two widely used remote sensing image databases show that the proposed method significantly improves the classification performance compared with other state-of-the-art methods.

##### Abstract (translated by Google)
随着深度学习的发展，监督学习经常采用卷积网络（CNN）对遥感图像进行分类。然而，由于可用标签数据量有限，监督式学习往往难以实施。因此，我们提出了一种称为多层特征匹配生成对抗网络（MARTA GANs）的无监督模型来学习仅使用未标记数据的表示。 MARTA GANs包含一个生成模型$ G $和一个判别模型$ D $。我们把$ D $当作特征提取器。为了适应遥感数据的复杂属性，我们使用融合层来融合中间层和全局特征。 $ G $可以产生许多与训练数据相似的图像;因此，$ D $可以使用$ G $提供的训练数据更好地表示遥感图像。在两个广泛使用的遥感影像数据库上的分类结果表明，与其他最先进的方法相比，所提出的方法显着提高了分类性能。

##### URL
[https://arxiv.org/abs/1612.08879](https://arxiv.org/abs/1612.08879)

##### PDF
[https://arxiv.org/pdf/1612.08879](https://arxiv.org/pdf/1612.08879)

