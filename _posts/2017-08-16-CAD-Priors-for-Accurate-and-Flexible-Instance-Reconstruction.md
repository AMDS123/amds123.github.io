---
layout: post
title: "CAD Priors for Accurate and Flexible Instance Reconstruction"
date: 2017-08-16 21:38:53
categories: arXiv_CV
tags: arXiv_CV Object_Detection GAN Detection
author: Tolga Birdal, Slobodan Ilic
mathjax: true
---

* content
{:toc}

##### Abstract
We present an efficient and automatic approach for accurate reconstruction of instances of big 3D objects from multiple, unorganized and unstructured point clouds, in presence of dynamic clutter and occlusions. In contrast to conventional scanning, where the background is assumed to be rather static, we aim at handling dynamic clutter where background drastically changes during the object scanning. Currently, it is tedious to solve this with available methods unless the object of interest is first segmented out from the rest of the scene. We address the problem by assuming the availability of a prior CAD model, roughly resembling the object to be reconstructed. This assumption almost always holds in applications such as industrial inspection or reverse engineering. With aid of this prior acting as a proxy, we propose a fully enhanced pipeline, capable of automatically detecting and segmenting the object of interest from scenes and creating a pose graph, online, with linear complexity. This allows initial scan alignment to the CAD model space, which is then refined without the CAD constraint to fully recover a high fidelity 3D reconstruction, accurate up to the sensor noise level. We also contribute a novel object detection method, local implicit shape models (LISM) and give a fast verification scheme. We evaluate our method on multiple datasets, demonstrating the ability to accurately reconstruct objects from small sizes up to $125m^3$.

##### Abstract (translated by Google)
我们提出了一种有效的自动方法，用于在存在动态杂波和遮挡的情况下从多个未组织的和非结构化的点云精确重建大型3D对象的实例。与传统的扫描相比，背景被认为是相当静态的，我们的目标是处理背景在对象扫描过程中剧烈变化的动态杂波。目前，用可用的方法解决这个问题是非常繁琐的，除非感兴趣的对象首先从其余的场景中分离出来。我们通过假定可用的CAD模型解决了这个问题，大致类似于要重建的对象。这个假设几乎总是适用于工业检测或逆向工程等应用。借助此前的代理作用，我们提出了一个完全增强的流水线，能够自动检测和分割场景中感兴趣的对象，并在线创建一个线性复杂的姿态图。这允许初始扫描与CAD模型空间对齐，然后在没有CAD约束的情况下对CAD模型空间进行精修，以完全恢复高精度的3D重建，精确到传感器噪声水平。我们还提出了一种新的对象检测方法，局部隐式形状模型（LISM），并给出了一个快速的验证方案。我们在多个数据集上评估了我们的方法，展示了从小尺寸到高达1.25亿立方米的对象的精确重构能力。

##### URL
[https://arxiv.org/abs/1705.03111](https://arxiv.org/abs/1705.03111)

##### PDF
[https://arxiv.org/pdf/1705.03111](https://arxiv.org/pdf/1705.03111)

