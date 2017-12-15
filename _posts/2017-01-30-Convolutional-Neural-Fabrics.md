---
layout: post
title: "Convolutional Neural Fabrics"
date: 2017-01-30 12:28:29
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation CNN Image_Classification Semantic_Segmentation Classification
author: Shreyas Saxena, Jakob Verbeek
mathjax: true
---

* content
{:toc}

##### Abstract
Despite the success of CNNs, selecting the optimal architecture for a given task remains an open problem. Instead of aiming to select a single optimal architecture, we propose a "fabric" that embeds an exponentially large number of architectures. The fabric consists of a 3D trellis that connects response maps at different layers, scales, and channels with a sparse homogeneous local connectivity pattern. The only hyper-parameters of a fabric are the number of channels and layers. While individual architectures can be recovered as paths, the fabric can in addition ensemble all embedded architectures together, sharing their weights where their paths overlap. Parameters can be learned using standard methods based on back-propagation, at a cost that scales linearly in the fabric size. We present benchmark results competitive with the state of the art for image classification on MNIST and CIFAR10, and for semantic segmentation on the Part Labels dataset.

##### Abstract (translated by Google)
尽管CNN取得了成功，但为特定任务选择最佳架构仍然是一个悬而未决的问题。我们没有选择一个最佳的体系结构，而是提出了一个嵌入指数级大量体系结构的“结构”。结构包括一个3D网格，连接不同层次，尺度和通道的响应地图，具有稀疏均匀的本地连接模式。织物唯一的超参数是通道和层数。虽然单个架构可以恢复为路径，但是架构还可以将所有嵌入式架构集中在一起，在路径重叠的位置共享权重。可以使用基于反向传播的标准方法来学习参数，其成本可以在结构尺寸中线性缩放。我们提供基于MNIST和CIFAR10的图像分类技术的最新水平的基准测试结果，以及Part Labels数据集上的语义分割。

##### URL
[https://arxiv.org/abs/1606.02492](https://arxiv.org/abs/1606.02492)

##### PDF
[https://arxiv.org/pdf/1606.02492](https://arxiv.org/pdf/1606.02492)

