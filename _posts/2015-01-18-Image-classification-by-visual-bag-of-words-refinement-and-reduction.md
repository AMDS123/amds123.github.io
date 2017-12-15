---
layout: post
title: "Image classification by visual bag-of-words refinement and reduction"
date: 2015-01-18 12:46:11
categories: arXiv_CV
tags: arXiv_CV Image_Classification Classification
author: Zhiwu Lu, Liwei Wang, Ji-Rong Wen
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a new framework for visual bag-of-words (BOW) refinement and reduction to overcome the drawbacks associated with the visual BOW model which has been widely used for image classification. Although very influential in the literature, the traditional visual BOW model has two distinct drawbacks. Firstly, for efficiency purposes, the visual vocabulary is commonly constructed by directly clustering the low-level visual feature vectors extracted from local keypoints, without considering the high-level semantics of images. That is, the visual BOW model still suffers from the semantic gap, and thus may lead to significant performance degradation in more challenging tasks (e.g. social image classification). Secondly, typically thousands of visual words are generated to obtain better performance on a relatively large image dataset. Due to such large vocabulary size, the subsequent image classification may take sheer amount of time. To overcome the first drawback, we develop a graph-based method for visual BOW refinement by exploiting the tags (easy to access although noisy) of social images. More notably, for efficient image classification, we further reduce the refined visual BOW model to a much smaller size through semantic spectral clustering. Extensive experimental results show the promising performance of the proposed framework for visual BOW refinement and reduction.

##### Abstract (translated by Google)
为了克服与视觉BOW模型相关的缺陷，本文提出了一种新的视觉袋装（BOW）细化和缩减框架，该模型已被广泛用于图像分类。尽管在文献中很有影响力，但传统的视觉BOW模型有两个明显的缺点。首先，为了提高效率，视觉词汇通常是通过对从局部关键点提取的低级视觉特征向量进行直接聚类来构建的，而不考虑图像的高级语义。也就是说，视觉BOW模型仍然受到语义差距的影响，因此可能导致更具挑战性的任务（例如社交图像分类）显着的性能下降。其次，通常生成数以千计的视觉词汇以在相对较大的图像数据集上获得更好的表现。由于这样大的词汇量，随后的图像分类可能需要很长时间。为了克服第一个缺点，我们通过利用社交图像的标签（易于访问，虽然有噪声）开发了基于图形的视觉BOW细化方法。更值得注意的是，对于高效的图像分类，我们通过语义谱聚类进一步将精致的视觉BOW模型缩小到更小的尺寸。广泛的实验结果表明，提出的视觉BOW细化和缩减框架的前景表现良好。

##### URL
[https://arxiv.org/abs/1501.04292](https://arxiv.org/abs/1501.04292)

##### PDF
[https://arxiv.org/pdf/1501.04292](https://arxiv.org/pdf/1501.04292)

