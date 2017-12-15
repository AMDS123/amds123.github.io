---
layout: post
title: "Inferring 3D Object Pose in RGB-D Images"
date: 2015-02-16 18:15:54
categories: arXiv_CV
tags: arXiv_CV CNN Detection
author: Saurabh Gupta, Pablo Arbeláez, Ross Girshick, Jitendra Malik
mathjax: true
---

* content
{:toc}

##### Abstract
The goal of this work is to replace objects in an RGB-D scene with corresponding 3D models from a library. We approach this problem by first detecting and segmenting object instances in the scene using the approach from Gupta et al. [13]. We use a convolutional neural network (CNN) to predict the pose of the object. This CNN is trained using pixel normals in images containing rendered synthetic objects. When tested on real data, it outperforms alternative algorithms trained on real data. We then use this coarse pose estimate along with the inferred pixel support to align a small number of prototypical models to the data, and place the model that fits the best into the scene. We observe a 48% relative improvement in performance at the task of 3D detection over the current state-of-the-art [33], while being an order of magnitude faster at the same time.

##### Abstract (translated by Google)
这项工作的目标是用一个库中的相应3D模型替换RGB-D场景中的对象。我们通过首先使用Gupta等人的方法检测和分割场景中的对象实例来解决这个问题。 [13]。我们使用卷积神经网络（CNN）来预测物体的姿态。使用包含渲染的合成对象的图像中的像素法线训练CNN。在真实数据上进行测试时，它优于在真实数据上训练的其他算法。然后，我们使用这种粗略的姿态估计以及推断的像素支持，将少量原型模型与数据对齐，并将最适合场景的模型放置。我们观察到三维检测的性能相对于目前最先进的技术[33]而言性能提高了48％，同时速度也提高了一个数量级。

##### URL
[https://arxiv.org/abs/1502.04652](https://arxiv.org/abs/1502.04652)

##### PDF
[https://arxiv.org/pdf/1502.04652](https://arxiv.org/pdf/1502.04652)

