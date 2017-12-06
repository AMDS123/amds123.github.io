---
layout: post
title: "Single Multi-feature detector for Amodal 3D Object Detection in RGB-D Images"
date: 2017-11-01 07:57:25
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Qianhui Luo, Huifang Ma, Yue Wang, Li Tang, Rong Xiong
mathjax: true
---

* content
{:toc}

##### Abstract
This paper aims at fast and high-accuracy amodal 3D object detections in RGB-D images, which requires a compact 3D bounding box around the whole object even under partial observations. To avoid the time-consuming proposals preextraction, we propose a single end-to-end framework based on the deep neural networks which hierarchically incorporates appearance and geometric features from 2.5D representation to 3D objects. The depth information has helped on reducing the output space of 3D bounding boxes into a manageable set of 3D anchor boxes with different sizes on multiple feature layers. At prediction time, in a convolutional fashion, the network predicts scores for categories and adjustments for locations, sizes and orientations of each 3D anchor box, which has considered multi-scale 2D features. Experiments on the challenging SUN RGB-D datasets show that our algorithm outperforms the state-of-the-art by 10.2 in mAP and is 88x faster than the Deep Sliding Shape. In addition, experiments suggest our algorithm even with a smaller input image size performs comparably but is 454x faster than the state-of-art on NYUV2 datasets.

##### Abstract (translated by Google)
本文针对RGB-D图像中快速高精度的节点三维物体检测，即使在局部观测的情况下，也需要在整个物体周围采用紧凑的三维边界框。为了避免耗时的提案，我们提出了一个基于深度神经网络的单一的端到端的框架，从2.5D表示到3D对象的层次结合外观和几何特征。深度信息有助于将三维边界框的输出空间缩小为多个要素图层上不同大小的可管理的一组三维锚定框。在预测时间，以卷积方式，网络预测了每个三维锚箱的位置，大小和方位的分类和调整，已经考虑了多尺度的二维特征。对具有挑战性的SUN RGB-D数据集进行的实验表明，我们的算法在mAP中的表现优于10.2，并且比Deep Sliding Shape快88倍。另外，实验表明，即使输入图像尺寸较小，我们的算法性能仍然可比，但是比NYUV2数据集上的最新技术快了454倍。

##### URL
[https://arxiv.org/abs/1711.00238](https://arxiv.org/abs/1711.00238)

