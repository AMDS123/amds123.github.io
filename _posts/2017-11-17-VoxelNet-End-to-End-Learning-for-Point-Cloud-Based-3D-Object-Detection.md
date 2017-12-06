---
layout: post
title: "VoxelNet: End-to-End Learning for Point Cloud Based 3D Object Detection"
date: 2017-11-17 04:25:24
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Yin Zhou, Oncel Tuzel
mathjax: true
---

* content
{:toc}

##### Abstract
Accurate detection of objects in 3D point clouds is a central problem in many applications, such as autonomous navigation, housekeeping robots, and augmented/virtual reality. To interface a highly sparse LiDAR point cloud with a region proposal network (RPN), most existing efforts have focused on hand-crafted feature representations, for example, a bird's eye view projection. In this work, we remove the need of manual feature engineering for 3D point clouds and propose VoxelNet, a generic 3D detection network that unifies feature extraction and bounding box prediction into a single stage, end-to-end trainable deep network. Specifically, VoxelNet divides a point cloud into equally spaced 3D voxels and transforms a group of points within each voxel into a unified feature representation through the newly introduced voxel feature encoding (VFE) layer. In this way, the point cloud is encoded as a descriptive volumetric representation, which is then connected to a RPN to generate detections. Experiments on the KITTI car detection benchmark show that VoxelNet outperforms the state-of-the-art LiDAR based 3D detection methods by a large margin. Furthermore, our network learns an effective discriminative representation of objects with various geometries, leading to encouraging results in 3D detection of pedestrians and cyclists, based on only LiDAR.

##### Abstract (translated by Google)
精确检测三维点云中的物体是很多应用中的核心问题，如自主导航，看家机器人和增强/虚拟现实。为了将一个高度稀疏的LiDAR点云与区域提议网络（RPN）连接起来，大多数现有的努力都集中在手工特征表示上，例如鸟瞰图投影。在这项工作中，我们消除了对三维点云进行手动特征工程的需求，并提出了一个通用的3D检测网络VoxelNet，它将特征提取和边界框预测统一到一个单一阶段的端到端可训练深度网络中。具体而言，VoxelNet将点云划分为等间隔的三维像素，并通过新引入的体素特征编码（VFE）层将每个体素内的一组点转换为统一的特征表示。这样，点云被编码为描述性体积表示，然后连接到RPN以生成检测结果。在KITTI汽车检测基准测试中的实验表明，VoxelNet大大超越了先进的基于LiDAR的3D检测方法。此外，我们的网络学习一个有效的不同几何形状的对象的区别表示，导致在仅基于LiDAR的行人和骑车人的3D检测方面令人鼓舞的结果。

##### URL
[https://arxiv.org/abs/1711.06396](https://arxiv.org/abs/1711.06396)

