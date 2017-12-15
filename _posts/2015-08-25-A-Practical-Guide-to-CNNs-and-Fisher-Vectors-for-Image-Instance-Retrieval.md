---
layout: post
title: "A Practical Guide to CNNs and Fisher Vectors for Image Instance Retrieval"
date: 2015-08-25 11:30:22
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Object_Detection Sparse CNN Image_Classification Classification Deep_Learning Detection
author: Vijay Chandrasekhar, Jie Lin, Olivier Morère, Hanlin Goh, Antoine Veillard
mathjax: true
---

* content
{:toc}

##### Abstract
With deep learning becoming the dominant approach in computer vision, the use of representations extracted from Convolutional Neural Nets (CNNs) is quickly gaining ground on Fisher Vectors (FVs) as favoured state-of-the-art global image descriptors for image instance retrieval. While the good performance of CNNs for image classification are unambiguously recognised, which of the two has the upper hand in the image retrieval context is not entirely clear yet. In this work, we propose a comprehensive study that systematically evaluates FVs and CNNs for image retrieval. The first part compares the performances of FVs and CNNs on multiple publicly available data sets. We investigate a number of details specific to each method. For FVs, we compare sparse descriptors based on interest point detectors with dense single-scale and multi-scale variants. For CNNs, we focus on understanding the impact of depth, architecture and training data on retrieval results. Our study shows that no descriptor is systematically better than the other and that performance gains can usually be obtained by using both types together. The second part of the study focuses on the impact of geometrical transformations such as rotations and scale changes. FVs based on interest point detectors are intrinsically resilient to such transformations while CNNs do not have a built-in mechanism to ensure such invariance. We show that performance of CNNs can quickly degrade in presence of rotations while they are far less affected by changes in scale. We then propose a number of ways to incorporate the required invariances in the CNN pipeline. Overall, our work is intended as a reference guide offering practically useful and simply implementable guidelines to anyone looking for state-of-the-art global descriptors best suited to their specific image instance retrieval problem.

##### Abstract (translated by Google)
随着深度学习成为计算机视觉中的主流方法，从卷积神经网络（CNN）提取的表示的使用正快速地在费希尔矢量（FV）上成为最受欢迎的用于图像实例检索的最先进的全局图像描述符。尽管CNN在图像分类方面的良好性能得到了明确的认可，但是在图像检索的背景下，哪一种方法占据上风还不是很清楚。在这项工作中，我们提出了一个全面的研究，系统地评估FV和CNN的图像检索。第一部分比较了FV和CNN在多个公开数据集上的表现。我们调查了每种方法的具体细节。对于FV，我们将基于兴趣点检测器的稀疏描述符与密集单尺度和多尺度变体进行比较。对于CNN，我们重点了解深度，架构和训练数据对检索结果的影响。我们的研究表明，没有任何描述符系统地比其他描述符更好，通常可以通过将两种类型结合使用来获得性能增益。本研究的第二部分着重于旋转和尺度变化等几何变换的影响。基于兴趣点检测器的FV对于这样的转换本质上是有弹性的，而CNN不具有确保这种不变性的内建机制。我们表明，CNNs的性能可以在旋转的情况下迅速降级，而它们受规模变化的影响要小得多。然后，我们提出了许多方法将所需的不变量纳入CNN管道。总体而言，我们的工作旨在作为参考指南，为寻求最适合其特定图像实例检索问题的最先进的全局描述符的任何人提供实用且简单可实施的准则。

##### URL
[https://arxiv.org/abs/1508.02496](https://arxiv.org/abs/1508.02496)

##### PDF
[https://arxiv.org/pdf/1508.02496](https://arxiv.org/pdf/1508.02496)

