---
layout: post
title: "Weakly Supervised PatchNets: Describing and Aggregating Local Patches for Scene Recognition"
date: 2017-02-21 21:12:53
categories: arXiv_CV
tags: arXiv_CV Weakly_Supervised CNN Recognition
author: Zhe Wang, Limin Wang, Yali Wang, Bowen Zhang, Yu Qiao
mathjax: true
---

* content
{:toc}

##### Abstract
Traditional feature encoding scheme (e.g., Fisher vector) with local descriptors (e.g., SIFT) and recent convolutional neural networks (CNNs) are two classes of successful methods for image recognition. In this paper, we propose a hybrid representation, which leverages the discriminative capacity of CNNs and the simplicity of descriptor encoding schema for image recognition, with a focus on scene recognition. To this end, we make three main contributions from the following aspects. First, we propose a patch-level and end-to-end architecture to model the appearance of local patches, called {\em PatchNet}. PatchNet is essentially a customized network trained in a weakly supervised manner, which uses the image-level supervision to guide the patch-level feature extraction. Second, we present a hybrid visual representation, called {\em VSAD}, by utilizing the robust feature representations of PatchNet to describe local patches and exploiting the semantic probabilities of PatchNet to aggregate these local patches into a global representation. Third, based on the proposed VSAD representation, we propose a new state-of-the-art scene recognition approach, which achieves an excellent performance on two standard benchmarks: MIT Indoor67 (86.2\%) and SUN397 (73.0\%).

##### Abstract (translated by Google)
具有局部描述符（例如，SIFT）和最近的卷积神经网络（CNN）的传统特征编码方案（例如，Fisher矢量）是用于图像识别的两类成功的方法。在本文中，我们提出了一个混合表示，利用CNN的区分能力和简单的描述符编码模式进行图像识别，重点放在场景识别上。为此，我们从以下三个方面做出主要贡献。首先，我们提出了一个补丁级和端到端的体系结构来模拟本地补丁的出现，称为{\ em PatchNet}。 PatchNet本质上是一个以弱监督方式训练的定制网络，它使用图像级监督来指导补丁级特征提取。其次，我们通过利用PatchNet的鲁棒特征表示来描述局部补丁并利用PatchNet的语义概率将这些局部补丁聚合成全局表示，从而提出了一种称为{\ em VSAD}的混合视觉表示。第三，基于提出的VSAD表示，我们提出了一种新的最先进的场景识别方法，它在两个标准基准：MIT Indoor67（86.2％）和SUN397（73.0％）上达到了极好的性能。

##### URL
[https://arxiv.org/abs/1609.00153](https://arxiv.org/abs/1609.00153)

##### PDF
[https://arxiv.org/pdf/1609.00153](https://arxiv.org/pdf/1609.00153)

