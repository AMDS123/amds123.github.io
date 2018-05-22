---
layout: post
title: "Spherical Convolutional Neural Network for 3D Point Clouds"
date: 2018-05-21 02:32:31
categories: arXiv_CV
tags: arXiv_CV Sparse CNN Classification
author: Haun Lei, Naveed Akhtar, Ajmal Mian
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a neural network for 3D point cloud processing that exploits `spherical' convolution kernels and octree partitioning of space. The proposed metric-based spherical kernels systematically quantize point neighborhoods to identify local geometric structures in data, while maintaining the properties of translation-invariance and asymmetry. The network architecture itself is guided by octree data structuring that takes full advantage of the sparse nature of irregular point clouds. We specify spherical kernels with the help of neurons in each layer that in turn are associated with spatial locations. We exploit this association to avert dynamic kernel generation during network training, that enables efficient learning with high resolution point clouds. We demonstrate the utility of the spherical convolutional neural network for 3D object classification on standard benchmark datasets.

##### Abstract (translated by Google)
我们提出了一个三维点云处理的神经网络，利用“球形”卷积核和八叉树空间分割。所提出的基于度量的球形核系统地量化点邻域以识别数据中的局部几何结构，同时保持平移不变性和不对称性。网络体系结构本身由八叉树数据结构指导，充分利用了不规则点云的稀疏性。我们在每层中的神经元的帮助下指定球形内核，而这些内核又与空间位置相关联。我们利用这种关联来避免网络培训期间的动态内核生成，这使得高分辨率点云能够进行高效的学习。我们证明了球形卷积神经网络在标准基准数据集上3D对象分类的效用。

##### URL
[https://arxiv.org/abs/1805.07872](https://arxiv.org/abs/1805.07872)

##### PDF
[https://arxiv.org/pdf/1805.07872](https://arxiv.org/pdf/1805.07872)

