---
layout: post
title: 'PointFusion: Deep Sensor Fusion for 3D Bounding Box Estimation'
date: 2017-11-29 14:25:13
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Danfei Xu, Dragomir Anguelov, Ashesh Jain
---

* content
{:toc}

##### Abstract
We present PointFusion, a generic 3D object detection method that leverages both image and 3D point cloud information. Unlike existing methods that either use multi-stage pipelines or hold sensor and dataset-specific assumptions, PointFusion is conceptually simple and application-agnostic. The image data and the raw point cloud data are independently processed by a CNN and a PointNet architecture, respectively. The resulting outputs are then combined by a novel fusion network, which predicts multiple 3D box hypotheses and their confidences, using the input 3D points as spatial anchors. We evaluate PointFusion on two distinctive datasets: the KITTI dataset that features driving scenes captured with a lidar-camera setup, and the SUN-RGBD dataset that captures indoor environments with RGB-D cameras. Our model is the first one that is able to perform better or on-par with the state-of-the-art on these diverse datasets without any dataset-specific model tuning.

##### Abstract (translated by Google)
我们介绍PointFusion，这是一种利用图像和3D点云信息的通用3D对象检测方法。与使用多级流水线或保持传感器和数据集特定假设的现有方法不同，PointFusion在概念上简单且与应用程序无关。图像数据和原始点云数据分别由CNN和PointNet架构独立处理。然后由一个新颖的融合网络将结果输出结合起来，该融合网络使用输入的3D点作为空间锚来预测多个3D盒子假设及其置信度。我们评估PointFusion两个独特的数据集：使用激光雷达相机设置拍摄驾驶场景的KITTI数据集，以及使用RGB-D摄像机捕获室内环境的SUN-RGBD数据集。我们的模型是第一个能够在这些不同的数据集上表现更好或者与最先进的技术相媲美的模型，而不需要任何数据集特定的模型调整。

##### URL
[https://arxiv.org/abs/1711.10871](https://arxiv.org/abs/1711.10871)

