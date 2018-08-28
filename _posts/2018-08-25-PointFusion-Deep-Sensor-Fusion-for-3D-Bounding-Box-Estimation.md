---
layout: post
title: "PointFusion: Deep Sensor Fusion for 3D Bounding Box Estimation"
date: 2018-08-25 22:22:44
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Danfei Xu, Dragomir Anguelov, Ashesh Jain
mathjax: true
---

* content
{:toc}

##### Abstract
We present PointFusion, a generic 3D object detection method that leverages both image and 3D point cloud information. Unlike existing methods that either use multi-stage pipelines or hold sensor and dataset-specific assumptions, PointFusion is conceptually simple and application-agnostic. The image data and the raw point cloud data are independently processed by a CNN and a PointNet architecture, respectively. The resulting outputs are then combined by a novel fusion network, which predicts multiple 3D box hypotheses and their confidences, using the input 3D points as spatial anchors. We evaluate PointFusion on two distinctive datasets: the KITTI dataset that features driving scenes captured with a lidar-camera setup, and the SUN-RGBD dataset that captures indoor environments with RGB-D cameras. Our model is the first one that is able to perform better or on-par with the state-of-the-art on these diverse datasets without any dataset-specific model tuning.

##### Abstract (translated by Google)
我们提出了PointFusion，一种利用图像和3D点云信息的通用3D对象检测方法。与使用多阶段管道或保持传感器和数据集特定假设的现有方法不同，PointFusion在概念上简单且与应用程序无关。图像数据和原始点云数据分别由CNN和PointNet架构独立处理。然后，由新的融合网络组合所得到的输出，该融合网络使用输入的3D点作为空间锚点来预测多个3D盒子假设及其置信度。我们在两个不同的数据集上评估PointFusion：KITTI数据集，其中包含利用激光雷达相机设置捕获的驾驶场景，以及使用RGB-D相机捕捉室内环境的SUN-RGBD数据集。我们的模型是第一个能够在不使用任何数据集特定模型调整的情况下在这些不同数据集上表现更好或与现有技术相媲美的模型。

##### URL
[http://arxiv.org/abs/1711.10871](http://arxiv.org/abs/1711.10871)

##### PDF
[http://arxiv.org/pdf/1711.10871](http://arxiv.org/pdf/1711.10871)

