---
layout: post
title: "Multi-View Stereo with Single-View Semantic Mesh Refinement"
date: 2017-08-24 20:12:42
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention
author: Andrea Romanoni, Marco Ciccone, Francesco Visin, Matteo Matteucci
mathjax: true
---

* content
{:toc}

##### Abstract
While 3D reconstruction is a well-established and widely explored research topic, semantic 3D reconstruction has only recently witnessed an increasing share of attention from the Computer Vision community. Semantic annotations allow in fact to enforce strong class-dependent priors, as planarity for ground and walls, which can be exploited to refine the reconstruction often resulting in non-trivial performance improvements. State-of-the art methods propose volumetric approaches to fuse RGB image data with semantic labels; even if successful, they do not scale well and fail to output high resolution meshes. In this paper we propose a novel method to refine both the geometry and the semantic labeling of a given mesh. We refine the mesh geometry by applying a variational method that optimizes a composite energy made of a state-of-the-art pairwise photo-metric term and a single-view term that models the semantic consistency between the labels of the 3D mesh and those of the segmented images. We also update the semantic labeling through a novel Markov Random Field (MRF) formulation that, together with the classical data and smoothness terms, takes into account class-specific priors estimated directly from the annotated mesh. This is in contrast to state-of-the-art methods that are typically based on handcrafted or learned priors. We are the first, jointly with the very recent and seminal work of [M. Blaha et al arXiv:1706.08336, 2017], to propose the use of semantics inside a mesh refinement framework. Differently from [M. Blaha et al arXiv:1706.08336, 2017], which adopts a more classical pairwise comparison to estimate the flow of the mesh, we apply a single-view comparison between the semantically annotated image and the current 3D mesh labels; this improves the robustness in case of noisy segmentations.

##### Abstract (translated by Google)
虽然三维重建是一个已被广泛研究和广泛研究的话题，但是语义三维重建最近才被计算机视觉社区所关注。语义标注实际上可以实施强类级依赖的先验，如地面和墙壁的平面性，可以利用这些平面来改进重建，这往往导致性能改进的不平凡。现有技术中的方法提出了将RGB图像数据与语义标签融合的体积法;即使成功，也不能很好地扩展，不能输出高分辨率的网格。在本文中，我们提出了一种新的方法来改善给定网格的几何和语义标签。我们通过应用一种变化的方法来优化网格的几何结构，这种方法优化了由最先进的成对光学测量术语和单视图术语组成的复合能量，该术语对三维网格的标签和那些的分割图像。我们还通过新颖的马尔可夫随机场（Markov Random Field，MRF）公式更新了语义标注，该公式与经典数据和平滑项一起考虑了直接从注释网格估计的类特定的先验。这与通常基于手工或学习先验的最先进方法形成对比。我们是第一个，与最近的和开创性的工作[M. Blaha et al arXiv：1706.08336，2017]，以提出在网格细化框架内使用语义。不同于[M. Blaha et al arXiv：1706.08336，2017]，采用更经典的成对比较来估计网格的流动，我们在语义标注的图像和当前的3D网格标签之间应用单视图比较;这在噪声分割的情况下提高了鲁棒性。

##### URL
[https://arxiv.org/abs/1708.04907](https://arxiv.org/abs/1708.04907)

##### PDF
[https://arxiv.org/pdf/1708.04907](https://arxiv.org/pdf/1708.04907)

