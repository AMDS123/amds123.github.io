---
layout: post
title: "Deep Projective 3D Semantic Segmentation"
date: 2017-05-09 16:59:41
categories: arXiv_CV
tags: arXiv_CV Segmentation Face Semantic_Segmentation Deep_Learning Prediction
author: Felix Järemo Lawin, Martin Danelljan, Patrik Tosteberg, Goutam Bhat, Fahad Shahbaz Khan, Michael Felsberg
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic segmentation of 3D point clouds is a challenging problem with numerous real-world applications. While deep learning has revolutionized the field of image semantic segmentation, its impact on point cloud data has been limited so far. Recent attempts, based on 3D deep learning approaches (3D-CNNs), have achieved below-expected results. Such methods require voxelizations of the underlying point cloud data, leading to decreased spatial resolution and increased memory consumption. Additionally, 3D-CNNs greatly suffer from the limited availability of annotated datasets. In this paper, we propose an alternative framework that avoids the limitations of 3D-CNNs. Instead of directly solving the problem in 3D, we first project the point cloud onto a set of synthetic 2D-images. These images are then used as input to a 2D-CNN, designed for semantic segmentation. Finally, the obtained prediction scores are re-projected to the point cloud to obtain the segmentation results. We further investigate the impact of multiple modalities, such as color, depth and surface normals, in a multi-stream network architecture. Experiments are performed on the recent Semantic3D dataset. Our approach sets a new state-of-the-art by achieving a relative gain of 7.9 %, compared to the previous best approach.

##### Abstract (translated by Google)
三维点云的语义分割是众多现实应用中的一个具有挑战性的问题。虽然深度学习已经彻底改变了图像语义分割领域，但其对点云数据的影响迄今为止还是有限的。基于3D深度学习方法（3D-CNN）的最近的尝试已经实现了低于预期的结果。这种方法需要基础点云数据的体素化，导致空间分辨率降低和内存消耗增加。另外，3D-CNN由于注释数据集的有限可用性而受到很大的影响。在本文中，我们提出了一个避免3D-CNN的限制的替代框架。我们首先将点云投影到一组合成​​的二维图像上，而不是直接用三维解决问题。然后，这些图像被用作2D-CNN的输入，用于语义分割。最后将得到的预测分数重新投影到点云上，得到分割结果。我们在多流网络架构中进一步研究多种模态的影响，如颜色，深度和曲面法线。实验是在最近的Semantic3D数据集上进行的。与以前的最佳方法相比，我们的方法设定了一个新的最新技术，实现7.9％的相对收益。

##### URL
[https://arxiv.org/abs/1705.03428](https://arxiv.org/abs/1705.03428)

##### PDF
[https://arxiv.org/pdf/1705.03428](https://arxiv.org/pdf/1705.03428)

