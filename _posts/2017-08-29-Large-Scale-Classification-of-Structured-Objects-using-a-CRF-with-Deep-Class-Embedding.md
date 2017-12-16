---
layout: post
title: "Large-Scale Classification of Structured Objects using a CRF with Deep Class Embedding"
date: 2017-08-29 13:06:25
categories: arXiv_CV
tags: arXiv_CV Sparse Embedding CNN Optimization Classification Deep_Learning Relation
author: Eran Goldman, Jacob Goldberger
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a novel deep learning architecture to classify structured objects in datasets with a large number of visually similar categories. We model sequences of images as linear-chain CRFs, and jointly learn the parameters from both local-visual features and neighboring classes. The visual features are computed by convolutional layers, and the class embeddings are learned by factorizing the CRF pairwise potential matrix. This forms a highly nonlinear objective function which is trained by optimizing a local likelihood approximation with batch-normalization. This model overcomes the difficulties of existing CRF methods to learn the contextual relationships thoroughly when there is a large number of classes and the data is sparse. The performance of the proposed method is illustrated on a huge dataset that contains images of retail-store product displays, taken in varying settings and viewpoints, and shows significantly improved results compared to linear CRF modeling and unnormalized likelihood optimization.

##### Abstract (translated by Google)
本文提出了一种新颖的深度学习体系结构来对具有大量视觉相似类别的数据集中的结构化对象进行分类。我们将图像序列建模为线性CRF，并从局部视觉特征和邻近类中共同学习参数。视觉特征由卷积层计算，并且通过因式分解CRF成对的势能矩阵来学习类别嵌入。这形成了一个高度非线性的目标函数，通过批量归一化优化局部似然近似来训练。该模型克服了现有CRF方法存在大量类且数据稀疏时需要深入了解上下文关系的困难。所提出的方法的性能在包含零售商店产品显示的图像的巨大数据集上进行说明，所述图像以不同的设置和视点呈现，并且与线性CRF建模和非标准化似然性优化相比显示出显着改善的结果。

##### URL
[https://arxiv.org/abs/1705.07420](https://arxiv.org/abs/1705.07420)

##### PDF
[https://arxiv.org/pdf/1705.07420](https://arxiv.org/pdf/1705.07420)

