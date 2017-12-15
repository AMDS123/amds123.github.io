---
layout: post
title: "Creating Simplified 3D Models with High Quality Textures"
date: 2016-02-22 04:45:43
categories: arXiv_CV
tags: arXiv_CV
author: Song Liu, Wanqing Li, Philip Ogunbona, Yang-Wai Chow
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents an extension to the KinectFusion algorithm which allows creating simplified 3D models with high quality RGB textures. This is achieved through (i) creating model textures using images from an HD RGB camera that is calibrated with Kinect depth camera, (ii) using a modified scheme to update model textures in an asymmetrical colour volume that contains a higher number of voxels than that of the geometry volume, (iii) simplifying dense polygon mesh model using quadric-based mesh decimation algorithm, and (iv) creating and mapping 2D textures to every polygon in the output 3D model. The proposed method is implemented in real-time by means of GPU parallel processing. Visualization via ray casting of both geometry and colour volumes provides users with a real-time feedback of the currently scanned 3D model. Experimental results show that the proposed method is capable of keeping the model texture quality even for a heavily decimated model and that, when reconstructing small objects, photorealistic RGB textures can still be reconstructed.

##### Abstract (translated by Google)
本文介绍了KinectFusion算法的扩展，该算法允许创建具有高质量RGB纹理的简化3D模型。这是通过以下方式实现的：（i）使用来自使用Kinect深度相机校准的HD RGB相机的图像创建模型纹理，（ii）使用修改的方案来更新不对称颜色体积中的模型纹理， （iii）使用基于二次方的网格抽取算法来简化稠密多边形网格模型，以及（iv）在输出3D模型中的每个多边形上创建并映射2D纹理。所提出的方法通过GPU并行处理实时实现。通过几何和颜色体积的光线投射进行可视化，为用户提供当前扫描的3D模型的实时反馈。实验结果表明，所提出的方法能够保持模型纹理质量，甚至对于大量抽取模型，并且在重建小物体时，照片级逼真的RGB纹理仍然可以被重建。

##### URL
[https://arxiv.org/abs/1602.06645](https://arxiv.org/abs/1602.06645)

##### PDF
[https://arxiv.org/pdf/1602.06645](https://arxiv.org/pdf/1602.06645)

