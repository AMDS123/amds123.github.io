---
layout: post
title: "Region-based semantic segmentation with end-to-end training"
date: 2016-07-26 12:46:51
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Classification
author: Holger Caesar, Jasper Uijlings, Vittorio Ferrari
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel method for semantic segmentation, the task of labeling each pixel in an image with a semantic class. Our method combines the advantages of the two main competing paradigms. Methods based on region classification offer proper spatial support for appearance measurements, but typically operate in two separate stages, none of which targets pixel labeling performance at the end of the pipeline. More recent fully convolutional methods are capable of end-to-end training for the final pixel labeling, but resort to fixed patches as spatial support. We show how to modify modern region-based approaches to enable end-to-end training for semantic segmentation. This is achieved via a differentiable region-to-pixel layer and a differentiable free-form Region-of-Interest pooling layer. Our method improves the state-of-the-art in terms of class-average accuracy with 64.0% on SIFT Flow and 49.9% on PASCAL Context, and is particularly accurate at object boundaries.

##### Abstract (translated by Google)
我们提出了一种新的语义分割方法，即用语义类对图像中的每个像素进行标记。我们的方法结合了两个主要竞争范式的优点。基于区域分类的方法为外观测量提供适当的空间支持，但是通常在两个单独的阶段中操作，没有一个目标在流水线结束时针对像素标记性能。最近的完全卷积方法能够进行最终像素标记的端对端训练，但求助于固定的补丁作为空间支持。我们展示了如何修改现代基于区域的方法，以实现语义分割的端到端培训。这是通过一个可微区域到像素层和一个可区分的自由形式的兴趣区域共享层实现的。我们的方法在类平均准确度方面提高了最新的水平，SIFT Flow为64.0％，PASCAL Context为49.9％，在对象边界处尤其准确。

##### URL
[https://arxiv.org/abs/1607.07671](https://arxiv.org/abs/1607.07671)

##### PDF
[https://arxiv.org/pdf/1607.07671](https://arxiv.org/pdf/1607.07671)

