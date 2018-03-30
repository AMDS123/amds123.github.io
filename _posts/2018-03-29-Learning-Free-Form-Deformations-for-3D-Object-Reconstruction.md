---
layout: post
title: "Learning Free-Form Deformations for 3D Object Reconstruction"
date: 2018-03-29 05:56:15
categories: arXiv_CV
tags: arXiv_CV Segmentation Face Semantic_Segmentation Deep_Learning Relation
author: Dominic Jack, Jhony K. Pontes, Sridha Sridharan, Clinton Fookes, Sareh Shirazi, Frederic Maire, Anders Eriksson
mathjax: true
---

* content
{:toc}

##### Abstract
Representing 3D shape in deep learning frameworks in an accurate, efficient and compact manner still remains an open challenge. Most existing work addresses this issue by employing voxel-based representations. While these approaches benefit greatly from advances in computer vision by generalizing 2D convolutions to the 3D setting, they also have several considerable drawbacks. The computational complexity of voxel-encodings grows cubically with the resolution thus limiting such representations to low-resolution 3D reconstruction. In an attempt to solve this problem, point cloud representations have been proposed. Although point clouds are more efficient than voxel representations as they only cover surfaces rather than volumes, they do not encode detailed geometric information about relationships between points. In this paper we propose a method to learn free-form deformations (FFD) for the task of 3D reconstruction from a single image. By learning to deform points sampled from a high-quality mesh, our trained model can be used to produce arbitrarily dense point clouds or meshes with fine-grained geometry. We evaluate our proposed framework on both synthetic and real-world data and achieve state-of-the-art results on point-cloud and volumetric metrics. Additionally, we qualitatively demonstrate its applicability to label transferring for 3D semantic segmentation.

##### Abstract (translated by Google)
以精确，高效和紧凑的方式在深度学习框架中表现3D形状仍然是一个公开挑战。大多数现有的工作通过采用基于体素的表示来解决这个问题。虽然这些方法通过将2D卷积一般化到3D设置而从计算机视觉的进步中获益很大，但它们也有几个相当大的缺点。体素编码的计算复杂度随着分辨率而立体增长，因此将这种表示限制为低分辨率3D重建。为了解决这个问题，已经提出了点云表示。尽管点云比体素表示更有效，因为它们只覆盖表面而不是体积，但它们不编码关于点之间关系的详细几何信息。在本文中，我们提出了一种方法来学习自由形变（FFD）的任务从一个单一的三维重建图像。通过学习对从高质量网格中采样的点进行变形，我们的训练模型可用于生成具有细粒几何图形的任意稠密点云或网格。我们评估了我们提出的合成和现实世界数据框架，并在点云和体积指标上实现了最先进的结果。另外，我们定性地证明了它适用于3D语义分割的标签传输。

##### URL
[http://arxiv.org/abs/1803.10932](http://arxiv.org/abs/1803.10932)

##### PDF
[http://arxiv.org/pdf/1803.10932](http://arxiv.org/pdf/1803.10932)

