---
layout: post
title: "Complex Relations in a Deep Structured Prediction Model for Fine Image Segmentation"
date: 2018-05-24 00:21:40
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Inference Deep_Learning Prediction Relation
author: Cristina Mata, Guy Ben-Yosef, Boris Katz
mathjax: true
---

* content
{:toc}

##### Abstract
Many deep learning architectures for semantic segmentation involve a Fully Convolutional Neural Network (FCN) followed by a Conditional Random Field (CRF) to carry out inference over an image. These models typically involve unary potentials based on local appearance features computed by FCNs, and binary potentials based on the displacement between pixels. We show that while current methods succeed in segmenting whole objects, they perform poorly in situations involving a large number of object parts. We therefore suggest incorporating into the inference algorithm additional higher-order potentials inspired by the way humans identify and localize parts. We incorporate two relations that were shown to be useful to human object identification - containment and attachment - into the energy term of the CRF and evaluate their performance on the Pascal VOC Parts dataset. Our experimental results show that the segmentation of fine parts is positively affected by the addition of these two relations, and that the segmentation of fine parts can be further influenced by complex structural features.

##### Abstract (translated by Google)
许多用于语义分割的深度学习体系结构涉及完全卷积神经网络（FCN），随后是条件随机场（CRF）以对图像执行推理。这些模型通常涉及基于由FCN计算的局部外观特征的一元电位，以及基于像素之间的位移的二元电位。我们表明，尽管当前的方法成功地分割了整个对象，但在涉及大量对象部分的情况下，它们表现不佳。因此，我们建议在推理算法中纳入由人类识别和定位零件的方式所激发的更高阶潜能。我们将两种显示对人体识别有用的关系 - 遏制和附着 - 纳入CRF的能量术语中，并评估它们在Pascal VOC部件数据集上的表现。我们的实验结果表明，精细部分的分割受到这两个关系的附加的正面影响，并且精细部分的分割可以进一步受到复杂结构特征的影响。

##### URL
[http://arxiv.org/abs/1805.09462](http://arxiv.org/abs/1805.09462)

##### PDF
[http://arxiv.org/pdf/1805.09462](http://arxiv.org/pdf/1805.09462)

