---
layout: post
title: "SfM-Net: Learning of Structure and Motion from Video"
date: 2017-04-25 17:30:05
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Sudheendra Vijayanarasimhan, Susanna Ricco, Cordelia Schmid, Rahul Sukthankar, Katerina Fragkiadaki
mathjax: true
---

* content
{:toc}

##### Abstract
We propose SfM-Net, a geometry-aware neural network for motion estimation in videos that decomposes frame-to-frame pixel motion in terms of scene and object depth, camera motion and 3D object rotations and translations. Given a sequence of frames, SfM-Net predicts depth, segmentation, camera and rigid object motions, converts those into a dense frame-to-frame motion field (optical flow), differentiably warps frames in time to match pixels and back-propagates. The model can be trained with various degrees of supervision: 1) self-supervised by the re-projection photometric error (completely unsupervised), 2) supervised by ego-motion (camera motion), or 3) supervised by depth (e.g., as provided by RGBD sensors). SfM-Net extracts meaningful depth estimates and successfully estimates frame-to-frame camera rotations and translations. It often successfully segments the moving objects in the scene, even though such supervision is never provided.

##### Abstract (translated by Google)
我们提出SfM-Net，这是一个基于几何意识的神经网络，用于视频中的运动估计，根据场景和对象深度，相机运动和3D对象旋转和平移来分解帧到帧的像素运动。给定一系列帧，SfM-Net预测深度，分割，相机和刚体运动，将这些运动转化为密集的帧到帧运动场（光流），并按时间微调帧以匹配像素和向后传播。该模型可以通过不同程度的监督进行训练：1）通过重新投影光度误差（完全无监督）进行自我监督; 2）由自我运动（相机运动）监督;或3）深度监督由RGBD传感器提供）。 SfM-Net提取有意义的深度估计并成功估计帧到帧的相机旋转和平移。它经常成功地将场景中的移动物体分割，尽管从未提供这种监视。

##### URL
[https://arxiv.org/abs/1704.07804](https://arxiv.org/abs/1704.07804)

##### PDF
[https://arxiv.org/pdf/1704.07804](https://arxiv.org/pdf/1704.07804)

