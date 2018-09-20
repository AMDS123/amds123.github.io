---
layout: post
title: "SilhoNet: An RGB Method for 3D Object Pose Estimation and Grasp Planning"
date: 2018-09-18 19:15:38
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN
author: Gideon Billings, Matthew Johnson-Roberson
mathjax: true
---

* content
{:toc}

##### Abstract
Autonomous robot manipulation often involves both estimating the pose of the object to be manipulated and selecting a viable grasp point. Methods using RGB-D data have shown great success in solving these problems. However, there are situations where cost constraints or the working environment may limit the use of RGB-D sensors. When limited to monocular camera data only, both the problem of object pose estimation and of grasp point selection are very challenging. In the past, research has focused on solving these problems separately. In this work, we introduce a novel method called SilhoNet that bridges the gap between these two tasks. We use a Convolutional Neural Network (CNN) pipeline that takes in ROI proposals to simultaneously predict an intermediate silhouette representation for objects with an associated occlusion mask. The 3D pose is then regressed from the predicted silhouettes. Grasp points from a precomputed database are filtered by back-projecting them onto the occlusion mask to find which points are visible in the scene. We show that our method achieves better overall performance than the state-of-the art PoseCNN network for 3D pose estimation on the YCB-video dataset.

##### Abstract (translated by Google)
自主机器人操纵通常涉及估计待操纵物体的姿势和选择可行的抓握点。使用RGB-D数据的方法在解决这些问题方面取得了巨大成功。然而，存在成本限制或工作环境可能限制RGB-D传感器的使用的情况。当仅限于单目相机数据时，对象姿势估计和抓握点选择的问题都是非常具有挑战性的。过去，研究的重点是分别解决这些问题。在这项工作中，我们引入了一种名为SilhoNet的新方法，它弥合了这两项任务之间的差距。我们使用卷积神经网络（CNN）管道，该管道接受ROI建议以同时预测具有相关遮挡掩模的对象的中间轮廓表示。然后从预测的轮廓回归3D姿势。从预先计算的数据库中抓取点通过将它们反投影到遮挡遮罩上来过滤，以找出场景中可见的点。我们表明，我们的方法比YCB视频数据集上用于3D姿态估计的最先进的PoseCNN网络实现了更好的整体性能。

##### URL
[http://arxiv.org/abs/1809.06893](http://arxiv.org/abs/1809.06893)

##### PDF
[http://arxiv.org/pdf/1809.06893](http://arxiv.org/pdf/1809.06893)

