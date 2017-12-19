---
layout: post
title: "Adapted sampling for 3D X-ray computed tomography"
date: 2015-07-29 06:30:04
categories: arXiv_CV
tags: arXiv_CV Sparse GAN Face
author: Anthony Cazasnoves, Fanny Buyens, Sylvie Sevestre
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we introduce a method to build an adapted mesh representation of a 3D object for X-Ray tomography reconstruction. Using this representation, we provide means to reduce the computational cost of reconstruction by way of iterative algorithms. The adapted sampling of the reconstruction space is directly obtained from the projection dataset and prior to any reconstruction. It is built following two stages : firstly, 2D structural information is extracted from the projection images and is secondly merged in 3D to obtain a 3D pointcloud sampling the interfaces of the object. A relevant mesh is then built from this cloud by way of tetrahedralization. Critical parameters selections have been automatized through a statistical framework, thus avoiding dependence on users expertise. Applying this approach on geometrical shapes and on a 3D Shepp-Logan phantom, we show the relevance of such a sampling - obtained in a few seconds - and the drastic decrease in cells number to be estimated during reconstruction when compared to the usual regular voxel lattice. A first iterative reconstruction of the Shepp-Logan using this kind of sampling shows the relevant advantages in terms of low dose or sparse acquisition sampling contexts. The method can also prove useful for other applications such as finite element method computations.

##### Abstract (translated by Google)
在本文中，我们介绍一种方法来建立一个三维物体的X射线断层摄影重建的自适应网格表示。使用这种表示，我们提供了通过迭代算法降低重构的计算成本的手段。重建空间的自适应采样直接从投影数据集获得，并在任何重建之前。它建立在以下两个阶段：首先，从投影图像中提取二维结构信息，然后二维合并成三维，以获得对象的界面的三维点云。然后通过四面体化从这个云中建立相关的网格。关键参数选择已通过统计框架自动化，从而避免依赖用户的专业知识。在几何形状和3D Shepp-Logan体模上应用这种方法，我们展示了这种采样的相关性 - 在几秒钟内获得 - 与通常的规则体素格子相比，在重建期间要估计的细胞数量急剧下降。使用这种采样的Shepp-Logan的第一次迭代重构显示了在低剂量或稀疏采集采样上下文方面的相关优点。该方法也可以证明对其他应用如有限元方法计算有用。

##### URL
[https://arxiv.org/abs/1507.08030](https://arxiv.org/abs/1507.08030)

##### PDF
[https://arxiv.org/pdf/1507.08030](https://arxiv.org/pdf/1507.08030)

