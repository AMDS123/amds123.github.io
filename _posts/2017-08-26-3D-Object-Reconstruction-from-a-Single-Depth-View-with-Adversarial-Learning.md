---
layout: post
title: "3D Object Reconstruction from a Single Depth View with Adversarial Learning"
date: 2017-08-26 13:46:21
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Bo Yang, Hongkai Wen, Sen Wang, Ronald Clark, Andrew Markham, Niki Trigoni
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel 3D-RecGAN approach, which reconstructs the complete 3D structure of a given object from a single arbitrary depth view using generative adversarial networks. Unlike the existing work which typically requires multiple views of the same object or class labels to recover the full 3D geometry, the proposed 3D-RecGAN only takes the voxel grid representation of a depth view of the object as input, and is able to generate the complete 3D occupancy grid by filling in the occluded/missing regions. The key idea is to combine the generative capabilities of autoencoders and the conditional Generative Adversarial Networks (GAN) framework, to infer accurate and fine-grained 3D structures of objects in high-dimensional voxel space. Extensive experiments on large synthetic datasets show that the proposed 3D-RecGAN significantly outperforms the state of the art in single view 3D object reconstruction, and is able to reconstruct unseen types of objects. Our code and data are available at: this https URL

##### Abstract (translated by Google)
在本文中，我们提出了一种新颖的3D-RecGAN方法，该方法使用生成的对抗网络从单个任意深度视图重建给定对象的完整3D结构。与通常需要多个相同对象或类标签的视图以恢复完整3D几何形状的现有工作不同，所提出的3D-RecGAN仅将对象的深度视图的体素网格表示作为输入，并且能够生成通过填写封闭/缺失区域完成3D占用网格。其关键思想是将自编码器的生成能力和条件生成对抗网络（GAN）框架结合起来，推导出高维体素空间中对象的准确细化的三维结构。在大型合成数据集上的大量实验表明，所提出的3D-RecGAN在单视图3D对象重建中明显优于现有技术，并能够重建看不见的类型的对象。我们的代码和数据可在以下网址获得：https：

##### URL
[https://arxiv.org/abs/1708.07969](https://arxiv.org/abs/1708.07969)

##### PDF
[https://arxiv.org/pdf/1708.07969](https://arxiv.org/pdf/1708.07969)

