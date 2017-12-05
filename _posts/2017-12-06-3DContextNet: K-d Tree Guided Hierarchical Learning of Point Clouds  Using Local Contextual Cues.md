---
layout: post
title: '3DContextNet: K-d Tree Guided Hierarchical Learning of Point Clouds  Using Local Contextual Cues'
date: 2017-12-06 01:34:45
categories: arXiv_CV
tags: arXiv_CV
author: Wei Zeng, Theo Gevers
---

* content
{:toc}

##### Abstract
3D data such as point clouds and meshes are becoming more and more available. The goal of this paper is to obtain 3D object and scene classification and semantic segmentation. Because point clouds have irregular formats, most of the existing methods convert the 3D data into multiple 2D projection images or 3D voxel grids. These representations are suited as input of conventional CNNs but they either ignore the underlying 3D geometrical structure or are constrained by data sparsity and computational complexity. Therefore, recent methods encode the coordinates of each point cloud to certain high dimensional features to cover the 3D space. However, by their design, these models are not able to sufficiently capture the local patterns. In this paper, we propose a method that directly uses point clouds as input and exploits the implicit space partition of k-d tree structure to learn the local contextual information and aggregate features at different scales hierarchically. Extensive experiments on challenging benchmarks show that our proposed model properly captures the local patterns to provide discriminative point set features. For the task of 3D scene semantic segmentation, our method outperforms the state-of-the-art on the challenging Stanford Large-Scale 3D Indoor Spaces Dataset(S3DIS) by a large margin.

##### Abstract (translated by Google)
诸如点云和网格之类的3D数据变得越来越可用。本文的目的是获得三维物体和场景的分类和语义分割。因为点云具有不规则的格式，所以现有的大多数方法将3D数据转换成多个2D投影图像或3D体素格网。这些表示适合作为常规CNN的输入，但是它们要么忽略潜在的3D几何结构，要么受到数据稀疏性和计算复杂性的限制。因此，最近的方法将每个点云的坐标编码为特定的高维特征来覆盖3D空间。但是，通过他们的设计，这些模型不能够充分捕捉当地的模式。在本文中，我们提出了一种直接使用点云作为输入的方法，利用k-d树结构的隐式空间分割来学习本地上下文信息，并在不同尺度上聚合特征。对具有挑战性的基准进行大量实验表明，我们提出的模型能够恰当地捕捉局部模式以提供判别性的点集特征。对于三维场景语义分割的任务，我们的方法大大优于具有挑战性的斯坦福大型3D室内空间数据集（S3DIS）的最新技术。

##### URL
[https://arxiv.org/abs/1711.11379](https://arxiv.org/abs/1711.11379)

