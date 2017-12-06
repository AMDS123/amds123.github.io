---
layout: post
title: "Deep Sliding Shapes for Amodal 3D Object Detection in RGB-D Images"
date: 2016-03-09 19:21:23
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection Recognition
author: Shuran Song, Jianxiong Xiao
mathjax: true
---

* content
{:toc}

##### Abstract
We focus on the task of amodal 3D object detection in RGB-D images, which aims to produce a 3D bounding box of an object in metric form at its full extent. We introduce Deep Sliding Shapes, a 3D ConvNet formulation that takes a 3D volumetric scene from a RGB-D image as input and outputs 3D object bounding boxes. In our approach, we propose the first 3D Region Proposal Network (RPN) to learn objectness from geometric shapes and the first joint Object Recognition Network (ORN) to extract geometric features in 3D and color features in 2D. In particular, we handle objects of various sizes by training an amodal RPN at two different scales and an ORN to regress 3D bounding boxes. Experiments show that our algorithm outperforms the state-of-the-art by 13.8 in mAP and is 200x faster than the original Sliding Shapes. All source code and pre-trained models will be available at GitHub.

##### Abstract (translated by Google)
我们重点研究RGB-D图像中节理三维物体检测的任务，其目的是在一定程度上生成一个度量形式的物体的三维边界框。我们介绍了Deep Sliding Shapes，一个3D ConvNet公式，它将RGB-D图像中的三维立体场景作为输入并输出三维对象边界框。在我们的方法中，我们提出了第一个三维地区建议网络（RPN），以从几何形状学习对象和第一个联合对象识别网络（ORN）来提取3D中的几何特征和2D中的颜色特征。特别是，我们通过训练两个不同尺度的节奏RPN和ORN来回归3D边界框，从而处理各种大小的对象。实验表明，我们的算法比现有技术的13.8更好，比原来的Sliding Shapes快200倍。所有源代码和预先训练好的模型都将在GitHub上提供。

##### URL
[https://arxiv.org/abs/1511.02300](https://arxiv.org/abs/1511.02300)

