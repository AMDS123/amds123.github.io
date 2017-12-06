---
layout: post
title: "Geometry-Based Region Proposals for Real-Time Robot Detection of Tabletop Objects"
date: 2017-03-14 18:51:18
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Deep_Learning Detection Recognition
author: Alexander Broad, Brenna Argall
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel object detection pipeline for localization and recognition in three dimensional environments. Our approach makes use of an RGB-D sensor and combines state-of-the-art techniques from the robotics and computer vision communities to create a robust, real-time detection system. We focus specifically on solving the object detection problem for tabletop scenes, a common environment for assistive manipulators. Our detection pipeline locates objects in a point cloud representation of the scene. These clusters are subsequently used to compute a bounding box around each object in the RGB space. Each defined patch is then fed into a Convolutional Neural Network (CNN) for object recognition. We also demonstrate that our region proposal method can be used to develop novel datasets that are both large and diverse enough to train deep learning models, and easy enough to collect that end-users can develop their own datasets. Lastly, we validate the resulting system through an extensive analysis of the accuracy and run-time of the full pipeline.

##### Abstract (translated by Google)
我们提出了一种新颖的物体检测流水线在三维环境中进行定位和识别。我们的方法使用了RGB-D传感器，并结合了机器人和计算机视觉社区的最新技术，创建了一个强大的实时检测系统。我们专注于解决桌面场景的物体检测问题，这是辅助操纵器的常见环境。我们的检测管道将对象定位在场景的点云表示中。随后使用这些群集计算RGB空间中每个对象周围的边界框。然后将每个定义的补丁馈送到卷积神经网络（CNN）中用于目标识别。我们还证明，我们的区域提案方法可以用来开发既大又丰富的新型数据集，以便训练深度学习模型，并且易于收集最终用户可以开发自己的数据集。最后，我们通过对整个管道的准确性和运行时间的广泛分析来验证所得到的系统。

##### URL
[https://arxiv.org/abs/1703.04665](https://arxiv.org/abs/1703.04665)

