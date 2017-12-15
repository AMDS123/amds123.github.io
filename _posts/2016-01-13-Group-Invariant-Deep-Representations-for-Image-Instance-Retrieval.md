---
layout: post
title: "Group Invariant Deep Representations for Image Instance Retrieval"
date: 2016-01-13 06:43:44
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification
author: Olivier Morère, Antoine Veillard, Jie Lin, Julie Petta, Vijay Chandrasekhar, Tomaso Poggio
mathjax: true
---

* content
{:toc}

##### Abstract
Most image instance retrieval pipelines are based on comparison of vectors known as global image descriptors between a query image and the database images. Due to their success in large scale image classification, representations extracted from Convolutional Neural Networks (CNN) are quickly gaining ground on Fisher Vectors (FVs) as state-of-the-art global descriptors for image instance retrieval. While CNN-based descriptors are generally remarked for good retrieval performance at lower bitrates, they nevertheless present a number of drawbacks including the lack of robustness to common object transformations such as rotations compared with their interest point based FV counterparts. In this paper, we propose a method for computing invariant global descriptors from CNNs. Our method implements a recently proposed mathematical theory for invariance in a sensory cortex modeled as a feedforward neural network. The resulting global descriptors can be made invariant to multiple arbitrary transformation groups while retaining good discriminativeness. Based on a thorough empirical evaluation using several publicly available datasets, we show that our method is able to significantly and consistently improve retrieval results every time a new type of invariance is incorporated. We also show that our method which has few parameters is not prone to overfitting: improvements generalize well across datasets with different properties with regard to invariances. Finally, we show that our descriptors are able to compare favourably to other state-of-the-art compact descriptors in similar bitranges, exceeding the highest retrieval results reported in the literature on some datasets. A dedicated dimensionality reduction step --quantization or hashing-- may be able to further improve the competitiveness of the descriptors.

##### Abstract (translated by Google)
大多数图像实例检索管线基于在查询图像和数据库图像之间被称为全局图像描述符的向量的比较。由于其在大规模图像分类方面的成功，从卷积神经网络（CNN）中提取的表示正迅速在Fisher矢量（FV）上获得，作为用于图像实例检索的最先进的全局描述符。尽管基于CNN的描述符通常在较低比特率下具有良好的检索性能，但它们仍然存在许多缺点，包括与基于兴趣点的FV对应物相比，缺乏对诸如旋转的常见对象变换的鲁棒性。在本文中，我们提出了一种计算来自CNN的不变全局描述符的方法。我们的方法实现了一个最近提出的数学理论不变感觉皮层建模为一个前馈神经网络的不变性。由此产生的全局描述符可以保持不变的多个任意转换组，同时保持良好的区别性。基于使用几个公开可用的数据集的彻底的经验性评估，我们显示，我们的方法能够显着和一致地改进检索结果，每当一种新的不变性被纳入。我们还表明，我们的参数很少的方法不容易出现过拟合：在不变性的不同性质的数据集之间的改进得到了很好的推广。最后，我们显示我们的描述符能够比较类似的比特范围内的其他最先进的紧凑描述符，超过了一些数据集文献中报道的最高检索结果。一个专门的降维步骤 - 量化或散列 - 可能能够进一步提高描述符的竞争力。

##### URL
[https://arxiv.org/abs/1601.02093](https://arxiv.org/abs/1601.02093)

##### PDF
[https://arxiv.org/pdf/1601.02093](https://arxiv.org/pdf/1601.02093)

