---
layout: post
title: "Rethinking Reprojection: Closing the Loop for Pose-aware ShapeReconstruction from a Single Image"
date: 2017-07-26 17:08:57
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Rui Zhu, Hamed Kiani Galoogahi, Chaoyang Wang, Simon Lucey
mathjax: true
---

* content
{:toc}

##### Abstract
An emerging problem in computer vision is the reconstruction of 3D shape and pose of an object from a single image. Hitherto, the problem has been addressed through the application of canonical deep learning methods to regress from the image directly to the 3D shape and pose labels. These approaches, however, are problematic from two perspectives. First, they are minimizing the error between 3D shapes and pose labels - with little thought about the nature of this label error when reprojecting the shape back onto the image. Second, they rely on the onerous and ill-posed task of hand labeling natural images with respect to 3D shape and pose. In this paper we define the new task of pose-aware shape reconstruction from a single image, and we advocate that cheaper 2D annotations of objects silhouettes in natural images can be utilized. We design architectures of pose-aware shape reconstruction which re-project the predicted shape back on to the image using the predicted pose. Our evaluation on several object categories demonstrates the superiority of our method for predicting pose-aware 3D shapes from natural images.

##### Abstract (translated by Google)
计算机视觉中出现的一个新问题是从单个图像重建3D形状和物体姿态。迄今为止，这个问题已经通过应用规范的深度学习方法从图像直接回归到三维形状和姿态标签中得到解决。然而，这些方法从两个角度来看是有问题的。首先，它们将3D形状和姿态标签之间的误差最小化 - 当将形状重新映射到图像上时，几乎没有考虑到该标签错误的性质。其次，他们依靠手工标记自然图像相对于三维形状和姿势的繁重和不适当的任务。在本文中，我们从单个图像定义姿态感知形状重建的新任务，并且我们主张可以利用在自然图像中更便宜的对物体轮廓的2D注释。我们设计姿态感知形状重建架构，使用预测的姿势将预测的形状重新映射到图像上。我们对几个对象类别的评估表明了我们的方法从自然图像预测姿态感知三维形状的优越性。

##### URL
[https://arxiv.org/abs/1707.04682](https://arxiv.org/abs/1707.04682)

##### PDF
[https://arxiv.org/pdf/1707.04682](https://arxiv.org/pdf/1707.04682)

