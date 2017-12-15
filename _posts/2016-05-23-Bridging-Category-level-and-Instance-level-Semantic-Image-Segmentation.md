---
layout: post
title: "Bridging Category-level and Instance-level Semantic Image Segmentation"
date: 2016-05-23 03:43:00
categories: arXiv_CV
tags: arXiv_CV Semantic_Instance_Segmentation Segmentation CNN Semantic_Segmentation
author: Zifeng Wu, Chunhua Shen, Anton van den Hengel
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an approach to instance-level image segmentation that is built on top of category-level segmentation. Specifically, for each pixel in a semantic category mask, its corresponding instance bounding box is predicted using a deep fully convolutional regression network. Thus it follows a different pipeline to the popular detect-then-segment approaches that first predict instances' bounding boxes, which are the current state-of-the-art in instance segmentation. We show that, by leveraging the strength of our state-of-the-art semantic segmentation models, the proposed method can achieve comparable or even better results to detect-then-segment approaches. We make the following contributions. (i) First, we propose a simple yet effective approach to semantic instance segmentation. (ii) Second, we propose an online bootstrapping method during training, which is critically important for achieving good performance for both semantic category segmentation and instance-level segmentation. (iii) As the performance of semantic category segmentation has a significant impact on the instance-level segmentation, which is the second step of our approach, we train fully convolutional residual networks to achieve the best semantic category segmentation accuracy. On the PASCAL VOC 2012 dataset, we obtain the currently best mean intersection-over-union score of 79.1%. (iv) We also achieve state-of-the-art results for instance-level segmentation.

##### Abstract (translated by Google)
我们提出了一种基于类别级分割的实例级图像分割方法。具体而言，对于语义类别掩码中的每个像素，使用深度完全卷积回归网络来预测其对应的实例边界框。因此，它遵循不同的流水线流行的检测，然后段的方法，首先预测实例的边界框，这是实例分割当前最先进的。我们表明，通过利用我们最先进的语义分割模型的优势，所提出的方法可以实现可比的甚至更好的结果来检测分段方法。我们做出以下贡献。 （一）首先，我们提出了一种简单而有效的语义实例分割方法。 （ii）其次，在训练过程中提出了一种在线引导方法，对于实现语义分类和实例级分割都具有非常重要的意义。 （3）由于语义类别分割的性能对实例分割有显着的影响，这是本文方法的第二步，我们对卷积残差网络进行训练，以达到最佳的语义分类精度。在PASCAL VOC 2012数据集中，我们获得了当前最好的79.1％的平均交叉分数。 （iv）我们也获得了实例级分割的最新结果。

##### URL
[https://arxiv.org/abs/1605.06885](https://arxiv.org/abs/1605.06885)

##### PDF
[https://arxiv.org/pdf/1605.06885](https://arxiv.org/pdf/1605.06885)

