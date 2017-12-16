---
layout: post
title: "Learning Spatial Regularization with Image-level Supervisions for Multi-label Image Classification"
date: 2017-03-31 08:49:43
categories: arXiv_CV
tags: arXiv_CV Regularization Attention Image_Classification Classification Relation
author: Feng Zhu, Hongsheng Li, Wanli Ouyang, Nenghai Yu, Xiaogang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-label image classification is a fundamental but challenging task in computer vision. Great progress has been achieved by exploiting semantic relations between labels in recent years. However, conventional approaches are unable to model the underlying spatial relations between labels in multi-label images, because spatial annotations of the labels are generally not provided. In this paper, we propose a unified deep neural network that exploits both semantic and spatial relations between labels with only image-level supervisions. Given a multi-label image, our proposed Spatial Regularization Network (SRN) generates attention maps for all labels and captures the underlying relations between them via learnable convolutions. By aggregating the regularized classification results with original results by a ResNet-101 network, the classification performance can be consistently improved. The whole deep neural network is trained end-to-end with only image-level annotations, thus requires no additional efforts on image annotations. Extensive evaluations on 3 public datasets with different types of labels show that our approach significantly outperforms state-of-the-arts and has strong generalization capability. Analysis of the learned SRN model demonstrates that it can effectively capture both semantic and spatial relations of labels for improving classification performance.

##### Abstract (translated by Google)
多标签图像分类是计算机视觉中的一个基本而又具有挑战性的任务。近年来，利用标签间的语义关系取得了很大的进展。然而，由于通常不提供标签的空间注释，传统的方法不能对多标签图像中的标签之间的基本空间关系进行建模。在本文中，我们提出了一个统一的深层神经网络，它只利用图像层面的监督来利用标签之间的语义和空间关系。给定一个多标签图像，我们提出的空间正则化网络（SRN）为所有标签生成注意图，并通过可学习的卷积捕捉它们之间的基本关系。通过将规则化的分类结果与ResNet-101网络的原始结果相结合，可以持续改善分类性能。整个深度神经网络仅通过图像级注释进行端对端训练，因此不需要额外的图像注释。对3种不同类型标签的公开数据集进行广泛的评估表明，我们的方法明显优于现有技术，具有较强的泛化能力。对学习到的SRN模型的分析表明，它可以有效地捕获标签的语义和空间关系，从而提高分类性能。

##### URL
[https://arxiv.org/abs/1702.05891](https://arxiv.org/abs/1702.05891)

##### PDF
[https://arxiv.org/pdf/1702.05891](https://arxiv.org/pdf/1702.05891)

