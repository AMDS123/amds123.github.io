---
layout: post
title: "Fusing Bird View LIDAR Point Cloud and Front View Camera Image for Deep Object Detection"
date: 2017-11-29 01:22:13
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Zining Wang, Wei Zhan, Masayoshi Tomizuka
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new method for fusing a LIDAR point cloud and camera-captured images in the deep convolutional neural network (CNN). The proposed method constructs a new layer called non-homogeneous pooling layer to transform features between bird view map and front view map. The sparse LIDAR point cloud is used to construct the mapping between the two maps. The pooling layer allows efficient fusion of the bird view and front view features at any stage of the network. This is favorable for the 3D-object detection using camera-LIDAR fusion in autonomous driving scenarios. A corresponding deep CNN is designed and tested on the KITTI bird view object detection dataset, which produces 3D bounding boxes from the bird view map. The fusion method shows particular benefit for detection of pedestrians in the bird view compared to other fusion-based object detection networks.

##### Abstract (translated by Google)
我们提出了一种在深度卷积神经网络（CNN）中融合LIDAR点云和相机捕获图像的新方法。所提出的方法构建了一个新的图层，称为非均匀池化层，在鸟瞰图与前视图之间进行特征转换。稀疏LIDAR点云用于构建两个地图之间的映射。池化层允许在网络的任何阶段有效地融合鸟瞰图和前视图特征。这对于在自主驾驶场景中使用相机-LIDAR融合的3D对象检测是有利的。在KITTI鸟视图对象检测数据集上设计并测试相应的深度CNN，从鸟瞰图中产生三维边界框。与其他基于融合的目标检测网络相比，融合方法在鸟瞰中显示出对行人检测的特别有益效果。

##### URL
[https://arxiv.org/abs/1711.06703](https://arxiv.org/abs/1711.06703)

