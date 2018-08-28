---
layout: post
title: "Dense 3D Object Reconstruction from a Single Depth View"
date: 2018-08-23 23:54:05
categories: arXiv_AI
tags: arXiv_AI Adversarial GAN
author: Bo Yang, Stefano Rosa, Andrew Markham, Niki Trigoni, Hongkai Wen
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel approach, 3D-RecGAN++, which reconstructs the complete 3D structure of a given object from a single arbitrary depth view using generative adversarial networks. Unlike existing work which typically requires multiple views of the same object or class labels to recover the full 3D geometry, the proposed 3D-RecGAN++ only takes the voxel grid representation of a depth view of the object as input, and is able to generate the complete 3D occupancy grid with a high resolution of 256^3 by recovering the occluded/missing regions. The key idea is to combine the generative capabilities of autoencoders and the conditional Generative Adversarial Networks (GAN) framework, to infer accurate and fine-grained 3D structures of objects in high-dimensional voxel space. Extensive experiments on large synthetic datasets and real-world Kinect datasets show that the proposed 3D-RecGAN++ significantly outperforms the state of the art in single view 3D object reconstruction, and is able to reconstruct unseen types of objects.

##### Abstract (translated by Google)
在本文中，我们提出了一种新颖的方法3D-RecGAN ++，它使用生成对抗网络从单个任意深度视图重建给定对象的完整3D结构。与通常需要相同对象或类标签的多个视图以恢复完整3D几何的现有工作不同，所提出的3D-RecGAN ++仅将对象的深度视图的体素网格表示作为输入，并且能够生成完整的通过恢复被遮挡/缺失区域，具有256 ^ 3的高分辨率的3D占用网格。关键思想是结合自动编码器的生成功能和条件生成对抗网络（GAN）框架，以推断高维体素空间中对象的精确和细粒度3D结构。对大型合成数据集和真实世界Kinect数据集的大量实验表明，所提出的3D-RecGAN ++在单视图3D对象重建中明显优于现有技术，并且能够重建看不见的对象类型。

##### URL
[http://arxiv.org/abs/1802.00411](http://arxiv.org/abs/1802.00411)

##### PDF
[http://arxiv.org/pdf/1802.00411](http://arxiv.org/pdf/1802.00411)

