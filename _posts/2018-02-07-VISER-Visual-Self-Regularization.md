---
layout: post
title: "VISER: Visual Self-Regularization"
date: 2018-02-07 18:55:01
categories: arXiv_CV
tags: arXiv_CV Regularization CNN Recognition
author: Hamid Izadinia, Pierre Garrigues
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we propose the use of large set of unlabeled images as a source of regularization data for learning robust visual representation. Given a visual model trained by a labeled dataset in a supervised fashion, we augment our training samples by incorporating large number of unlabeled data and train a semi-supervised model. We demonstrate that our proposed learning approach leverages an abundance of unlabeled images and boosts the visual recognition performance which alleviates the need to rely on large labeled datasets for learning robust representation. To increment the number of image instances needed to learn robust visual models in our approach, each labeled image propagates its label to its nearest unlabeled image instances. These retrieved unlabeled images serve as local perturbations of each labeled image to perform Visual Self-Regularization (VISER). To retrieve such visual self regularizers, we compute the cosine similarity in a semantic space defined by the penultimate layer in a fully convolutional neural network. We use the publicly available Yahoo Flickr Creative Commons 100M dataset as the source of our unlabeled image set and propose a distributed approximate nearest neighbor algorithm to make retrieval practical at that scale. Using the labeled instances and their regularizer samples we show that we significantly improve object categorization and localization performance on the MS COCO and Visual Genome datasets where objects appear in context.

##### Abstract (translated by Google)
在这项工作中，我们提出使用大量的未标记图像作为正则化数据的来源，用于学习鲁棒的视觉表示。给定一个以受监督的方式由标记数据集训练的视觉模型，我们通过整合大量未标记的数据并训练一个半监督模型来增加我们的训练样本。我们证明，我们提出的学习方法利用丰富的未标记图像，并提高了视觉识别性能，减轻了依赖于大型标记数据集来学习鲁棒表示的需要。为了增加在我们的方法中学习鲁棒视觉模型所需的图像实例的数量，每个标记图像将其标签传播到其最近的未标记图像实例。这些检索到的未标记图像用作每个标记图像的局部摄动以执行视觉自我正规化（VISER）。为了检索这样的视觉自调节器，我们在完全卷积神经网络中的倒数第二层所定义的语义空间中计算余弦相似度。我们使用公开的雅虎Flickr Creative Commons 100M数据集作为我们的未标记图像集的来源，并提出了一个分布式近似最近邻算法，使检索在这个规模实用。使用带标签的实例及其正则化程序样本，我们显示我们显着提高了对象出现在上下文中的MS COCO和Visual Genome数据集上的对象分类和本地化性能。

##### URL
[https://arxiv.org/abs/1802.02568](https://arxiv.org/abs/1802.02568)

##### PDF
[https://arxiv.org/pdf/1802.02568](https://arxiv.org/pdf/1802.02568)

