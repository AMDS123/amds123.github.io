---
layout: post
title: "3D Point Cloud Denoising using Graph Laplacian Regularization of a Low Dimensional Manifold Model"
date: 2018-03-20 04:29:46
categories: arXiv_CV
tags: arXiv_CV Regularization Salient Face
author: Jin Zeng, Gene Cheung, Michael Ng, Jiahao Pang, Cheng Yang
mathjax: true
---

* content
{:toc}

##### Abstract
3D point cloud - a new signal representation of volumetric objects - is a discrete collection of triples marking exterior object surface locations in 3D space. Conventional imperfect acquisition processes of 3D point cloud - e.g., stereo-matching from multiple viewpoint images or depth data acquired directly from active light sensors - imply non-negligible noise in the data. In this paper, we adopt a previously proposed low-dimensional manifold model for the surface patches in the point cloud and seek self-similar patches to denoise them simultaneously using the patch manifold prior. Due to discrete observations of the patches on the manifold, we approximate the manifold dimension computation defined in the continuous domain with a patch-based graph Laplacian regularizer and propose a new discrete patch distance measure to quantify the similarity between two same-sized surface patches for graph construction that is robust to noise. We show that our graph Laplacian regularizer has a natural graph spectral interpretation, and has desirable numerical stability properties via eigenanalysis. Extensive simulation results show that our proposed denoising scheme can outperform state-of-the-art methods in objective metrics and can better preserve visually salient structural features like edges.

##### Abstract (translated by Google)
3D点云 - 体积物体的新信号表示 - 是3D空间中标记外部物体表面位置的三元组的离散集合。 3D点云的常规不完美采集过程（例如，来自多个视点图像的立体匹配或从有源光传感器直接获取的深度数据）意味着数据中的不可忽略的噪声。在本文中，我们采用先前提出的低维流形模型用于点云中的曲面片，并寻找自相似的片来使用之前的片拼接头同时对其进行去噪。由于在流形上对斑块的离散观察，我们使用基于斑块的图形拉普拉斯正则化来逼近在连续域中定义的流形维数计算，并且提出一种新的离散斑块距离测量来量化两个相同大小的表面斑块之间的相似性图形结构对噪声强劲。我们表明，我们的图拉普拉斯正则化算子具有天然图谱解释，并通过本征分析具有理想的数值稳定性。广泛的仿真结果表明，我们提出的去噪方案可以超越客观指标中的最新方法，并且可以更好地保留视觉上突出的结构特征，如边缘。

##### URL
[http://arxiv.org/abs/1803.07252](http://arxiv.org/abs/1803.07252)

##### PDF
[http://arxiv.org/pdf/1803.07252](http://arxiv.org/pdf/1803.07252)

