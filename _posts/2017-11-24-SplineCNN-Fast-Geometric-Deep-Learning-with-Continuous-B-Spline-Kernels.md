---
layout: post
title: "SplineCNN: Fast Geometric Deep Learning with Continuous B-Spline Kernels"
date: 2017-11-24 10:33:05
categories: arXiv_CV
tags: arXiv_CV CNN Classification Deep_Learning
author: Matthias Fey, Jan Eric Lenssen, Frank Weichert, Heinrich Müller
mathjax: true
---

* content
{:toc}

##### Abstract
We present Spline-based Convolutional Neural Networks (SplineCNNs), a variant of deep neural networks for irregular structured and geometric input, e.g., graphs or meshes. Our main contribution is a novel convolution operator based on B-splines, that makes the computation time independent from the kernel size due to the local support property of the B-spline basis functions. As a result, we obtain a generalization of the traditional CNN convolution operator by using continuous kernel functions parametrized by a fixed number of trainable weights. In contrast to related approaches that filter in the spectral domain, the proposed method aggregates features purely in the spatial domain. As a main advantage, SplineCNN allows entire end-to-end training of deep architectures, using only the geometric structure as input, instead of handcrafted feature descriptors. For validation, we apply our method on tasks from the fields of image graph classification, shape correspondence and graph node classification, and show that it outperforms or pars state-of-the-art approaches while being significantly faster and having favorable properties like domain-independence.

##### Abstract (translated by Google)
我们提出基于样条线的卷积神经网络（SplineCNNs），一种用于不规则结构化和几何输入（例如图形或网格）的深度神经网络的变体。我们的主要贡献是基于B样条的新型卷积算子，由于B样条基函数的局部支持性质，使得计算时间与内核大小无关。因此，我们通过使用固定数量的可训练权重进行参数化的连续核函数来获得传统CNN卷积算子的推广。与在频域中过滤的相关方法相比，所提出的方法纯粹在空间域中聚合特征。作为一个主要优势，SplineCNN允许深层架构的整个端到端培训，只使用几何结构作为输入，而不是手工制作的特征描述符。为了进行验证，我们将该方法应用于图像图形分类，形状对应和图形节点分类等领域的任务，并且显示出其优于现有技术，同时速度更快，具有良好的性能，独立。

##### URL
[https://arxiv.org/abs/1711.08920](https://arxiv.org/abs/1711.08920)

##### PDF
[https://arxiv.org/pdf/1711.08920](https://arxiv.org/pdf/1711.08920)

