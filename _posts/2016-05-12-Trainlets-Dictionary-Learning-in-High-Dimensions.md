---
layout: post
title: "Trainlets: Dictionary Learning in High Dimensions"
date: 2016-05-12 16:37:09
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Jeremias Sulam, Boaz Ophir, Michael Zibulevsky, Michael Elad
mathjax: true
---

* content
{:toc}

##### Abstract
Sparse representations has shown to be a very powerful model for real world signals, and has enabled the development of applications with notable performance. Combined with the ability to learn a dictionary from signal examples, sparsity-inspired algorithms are often achieving state-of-the-art results in a wide variety of tasks. Yet, these methods have traditionally been restricted to small dimensions mainly due to the computational constraints that the dictionary learning problem entails. In the context of image processing, this implies handling small image patches. In this work we show how to efficiently handle bigger dimensions and go beyond the small patches in sparsity-based signal and image processing methods. We build our approach based on a new cropped wavelet decomposition, which enables a multi-scale analysis with virtually no border effects. We then employ this as the base dictionary within a double sparsity model to enable the training of adaptive dictionaries. To cope with the increase of training data, while at the same time improving the training performance, we present an Online Sparse Dictionary Learning (OSDL) algorithm to train this model effectively, enabling it to handle millions of examples. This work shows that dictionary learning can be up-scaled to tackle a new level of signal dimensions, obtaining large adaptable atoms that we call trainlets.

##### Abstract (translated by Google)
稀疏表示已经被证明是真实世界信号的非常强大的模型，并且已经使具有显着性能的应用的开发成为可能。结合从信号示例学习字典的能力，稀疏启发式算法通常在各种任务中获得最新的结果。然而，传统上这些方法限于小尺寸，主要是由于字典学习问题带来的计算限制。在图像处理的情况下，这意味着处理小的图像补丁。在这项工作中，我们展示了如何有效地处理更大的尺寸，超越基于稀疏的信号和图像处理方法中的小块。我们基于新的裁剪小波分解来构建我们的方法，其实现了几乎没有边界效应的多尺度分析。然后，我们将这个作为双重稀疏模型中的基本字典来启用对自适应字典的训练。为了应对训练数据的增加，同时提高训练性能，我们提出了一种在线稀疏字典学习（OSDL）算法来有效地训练这个模型，使其能够处理数百万个示例。这项工作表明，字典学习可以扩大到解决信号维度的一个新的水平，获得我们称之为trainlets大适应性原子。

##### URL
[https://arxiv.org/abs/1602.00212](https://arxiv.org/abs/1602.00212)

##### PDF
[https://arxiv.org/pdf/1602.00212](https://arxiv.org/pdf/1602.00212)

