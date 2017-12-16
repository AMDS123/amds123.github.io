---
layout: post
title: "3D Bounding Box Estimation Using Deep Learning and Geometry"
date: 2017-04-10 19:05:46
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Pose_Estimation CNN Semantic_Segmentation Deep_Learning Detection
author: Arsalan Mousavian, Dragomir Anguelov, John Flynn, Jana Kosecka
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method for 3D object detection and pose estimation from a single image. In contrast to current techniques that only regress the 3D orientation of an object, our method first regresses relatively stable 3D object properties using a deep convolutional neural network and then combines these estimates with geometric constraints provided by a 2D object bounding box to produce a complete 3D bounding box. The first network output estimates the 3D object orientation using a novel hybrid discrete-continuous loss, which significantly outperforms the L2 loss. The second output regresses the 3D object dimensions, which have relatively little variance compared to alternatives and can often be predicted for many object types. These estimates, combined with the geometric constraints on translation imposed by the 2D bounding box, enable us to recover a stable and accurate 3D object pose. We evaluate our method on the challenging KITTI object detection benchmark both on the official metric of 3D orientation estimation and also on the accuracy of the obtained 3D bounding boxes. Although conceptually simple, our method outperforms more complex and computationally expensive approaches that leverage semantic segmentation, instance level segmentation and flat ground priors and sub-category detection. Our discrete-continuous loss also produces state of the art results for 3D viewpoint estimation on the Pascal 3D+ dataset.

##### Abstract (translated by Google)
我们提出了一种从单个图像进行三维物体检测和姿态估计的方法。与目前仅回归物体的3D定向的技术相反，我们的方法首先使用深度卷积神经网络对相对稳定的3D物体属性进行回归，然后将这些估计与由2D物体边界框提供的几何约束组合，以产生完整的3D边界框。第一个网络输出使用新的混合离散连续损失来估计3D对象定向，其明显优于L2损失。第二个输出回归三维对象维度，与替代方案相比，方差相对较小，而且通常可以预测许多对象类型。这些估计结合二维边界框对平移的几何约束，使我们能够恢复稳定和准确的三维物体姿态。我们在具有挑战性的KITTI物体检测基准上对我们的方法进行评估，无论是3D方向估计的官方度量还是所获得的3D边界框的精度。虽然在概念上很简单，但我们的方法比利用语义分割，实例级别分割以及平坦地面先验和子类别检测的更复杂且计算更昂贵的方法更胜一筹。我们的离散连续损失也为Pascal 3D +数据集上的3D视点估计产生了最先进的结果。

##### URL
[https://arxiv.org/abs/1612.00496](https://arxiv.org/abs/1612.00496)

##### PDF
[https://arxiv.org/pdf/1612.00496](https://arxiv.org/pdf/1612.00496)

