---
layout: post
title: "Multiresolution Tree Networks for 3D Point Cloud Processing"
date: 2018-07-10 08:28:01
categories: arXiv_CV
tags: arXiv_CV Inference Classification
author: Matheus Gadelha, Rui Wang, Subhransu Maji
mathjax: true
---

* content
{:toc}

##### Abstract
We present multiresolution tree-structured networks to process point clouds for 3D shape understanding and generation tasks. Our network represents a 3D shape as a set of locality-preserving 1D ordered list of points at multiple resolutions. This allows efficient feed-forward processing through 1D convolutions, coarse-to-fine analysis through a multi-grid architecture, and it leads to faster convergence and small memory footprint during training. The proposed tree-structured encoders can be used to classify shapes and outperform existing point-based architectures on shape classification benchmarks, while tree-structured decoders can be used for generating point clouds directly and they outperform existing approaches for image-to-shape inference tasks learned using the ShapeNet dataset. Our model also allows unsupervised learning of point-cloud based shapes by using a variational autoencoder, leading to higher-quality generated shapes.

##### Abstract (translated by Google)
我们提出了多分辨率树状结构网络来处理点云，以便进行3D形状理解和生成任务。我们的网络将3D形状表示为一组保持位置的1D有序多点分辨率列表。这允许通过一维卷积进行高效的前馈处理，通过多网格架构进行粗到精分析，并且在训练期间可以实现更快的收敛和更小的内存占用。所提出的树形结构编码器可用于对形状进行分类，并在形状分类基准测试中优于现有的基于点的架构，而树形结构解码器可用于直接生成点云，并且它们优于现有的图像到形状推理任务方法使用ShapeNet数据集学习。我们的模型还允许通过使用变分自动编码器对基于点云的形状进行无监督学习，从而产生更高质量的生成形状。

##### URL
[http://arxiv.org/abs/1807.03520](http://arxiv.org/abs/1807.03520)

##### PDF
[http://arxiv.org/pdf/1807.03520](http://arxiv.org/pdf/1807.03520)

