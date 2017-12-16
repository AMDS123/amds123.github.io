---
layout: post
title: "OctNetFusion: Learning Depth Fusion from Data"
date: 2017-10-31 20:58:32
categories: arXiv_CV
tags: arXiv_CV Face Deep_Learning
author: Gernot Riegler, Ali Osman Ulusoy, Horst Bischof, Andreas Geiger
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a learning based approach to depth fusion, i.e., dense 3D reconstruction from multiple depth images. The most common approach to depth fusion is based on averaging truncated signed distance functions, which was originally proposed by Curless and Levoy in 1996. While this method is simple and provides great results, it is not able to reconstruct (partially) occluded surfaces and requires a large number frames to filter out sensor noise and outliers. Motivated by the availability of large 3D model repositories and recent advances in deep learning, we present a novel 3D CNN architecture that learns to predict an implicit surface representation from the input depth maps. Our learning based method significantly outperforms the traditional volumetric fusion approach in terms of noise reduction and outlier suppression. By learning the structure of real world 3D objects and scenes, our approach is further able to reconstruct occluded regions and to fill in gaps in the reconstruction. We demonstrate that our learning based approach outperforms both vanilla TSDF fusion as well as TV-L1 fusion on the task of volumetric fusion. Further, we demonstrate state-of-the-art 3D shape completion results.

##### Abstract (translated by Google)
在本文中，我们提出了一种基于学习的深度融合方法，即从多个深度图像进行密集的三维重建。最常见的深度融合方法是基于平均截断的有符号距离函数，最初由Curless和Levoy在1996年提出。虽然这种方法很简单并且提供了很好的结果，但它不能重建（部分）被遮挡的表面，并且需要大量帧来滤除传感器噪声和异常值。受到大型3D模型库的可用性以及深度学习的最新进展的启发，我们提出了一种新颖的3D CNN架构，学习如何从输入深度图预测隐式曲面表示。基于学习的方法在降噪和异常抑制方面明显优于传统的体积融合方法。通过学习真实世界三维物体和场景的结构，我们的方法可以进一步重建被遮挡的区域，填补重建空白。我们证明我们的基于学习的方法优于香草TSDF融合以及TV-L1融合体积融合的任务。此外，我们还展示了最先进的三维形状完成结果。

##### URL
[https://arxiv.org/abs/1704.01047](https://arxiv.org/abs/1704.01047)

##### PDF
[https://arxiv.org/pdf/1704.01047](https://arxiv.org/pdf/1704.01047)

