---
layout: post
title: "Hybrid CNN and Dictionary-Based Models for Scene Recognition and Domain Adaptation"
date: 2016-01-29 05:32:52
categories: arXiv_CV
tags: arXiv_CV CNN Recognition
author: Guo-Sen Xie, Xu-Yao Zhang, Shuicheng Yan, Cheng-Lin Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural network (CNN) has achieved state-of-the-art performance in many different visual tasks. Learned from a large-scale training dataset, CNN features are much more discriminative and accurate than the hand-crafted features. Moreover, CNN features are also transferable among different domains. On the other hand, traditional dictionarybased features (such as BoW and SPM) contain much more local discriminative and structural information, which is implicitly embedded in the images. To further improve the performance, in this paper, we propose to combine CNN with dictionarybased models for scene recognition and visual domain adaptation. Specifically, based on the well-tuned CNN models (e.g., AlexNet and VGG Net), two dictionary-based representations are further constructed, namely mid-level local representation (MLR) and convolutional Fisher vector representation (CFV). In MLR, an efficient two-stage clustering method, i.e., weighted spatial and feature space spectral clustering on the parts of a single image followed by clustering all representative parts of all images, is used to generate a class-mixture or a classspecific part dictionary. After that, the part dictionary is used to operate with the multi-scale image inputs for generating midlevel representation. In CFV, a multi-scale and scale-proportional GMM training strategy is utilized to generate Fisher vectors based on the last convolutional layer of CNN. By integrating the complementary information of MLR, CFV and the CNN features of the fully connected layer, the state-of-the-art performance can be achieved on scene recognition and domain adaptation problems. An interested finding is that our proposed hybrid representation (from VGG net trained on ImageNet) is also complementary with GoogLeNet and/or VGG-11 (trained on Place205) greatly.

##### Abstract (translated by Google)
卷积神经网络（CNN）已经在许多不同的视觉任务中实现了最先进的性能。从大规模训练数据集中学习，CNN特征比手工特征更具辨别性和准确性。而且CNN的特征也可以在不同的领域间转移。另一方面，传统的基于字典的特征（如BoW和SPM）包含更多的局部区分和结构信息，隐含在图像中。为了进一步提高性能，本文提出将CNN与基于字典的模型相结合进行场景识别和视觉域自适应。具体而言，基于经过良好调整的CNN模型（例如，AlexNet和VGGNet），进一步构建两个基于字典的表示，即中级局部表示（MLR）和卷积费希尔矢量表示（CFV）。在MLR中，一个有效的两阶段聚类方法，即对单个图像的部分进行加权空间和特征空间谱聚类，然后对所有图像的所有代表性部分进行聚类，用于生成类别混合或类别特定部分字典。之后，部分字典用于与多尺度图像输入一起操作以生成中间级别表示。在CFV中，利用多尺度和尺度比例的GMM训练策略来生成基于CNN的最后一个卷积层的Fisher向量。通过整合MLR，CFV和全连通层CNN特征的互补信息，可以实现现场识别和领域适应问题的最新性能。感兴趣的发现是我们提出的混合表示（来自在ImageNet上训练的VGG网络）也与GoogLeNet和/或VGG-11（在Place205上训练）相辅相成。

##### URL
[https://arxiv.org/abs/1601.07977](https://arxiv.org/abs/1601.07977)

##### PDF
[https://arxiv.org/pdf/1601.07977](https://arxiv.org/pdf/1601.07977)

