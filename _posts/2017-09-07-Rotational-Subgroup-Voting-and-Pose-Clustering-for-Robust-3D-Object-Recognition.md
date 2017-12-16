---
layout: post
title: "Rotational Subgroup Voting and Pose Clustering for Robust 3D Object Recognition"
date: 2017-09-07 08:54:20
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face Pose_Estimation Detection Relation Recognition
author: Anders Glent Buch, Lilita Kiforenko, Dirk Kraft
mathjax: true
---

* content
{:toc}

##### Abstract
It is possible to associate a highly constrained subset of relative 6 DoF poses between two 3D shapes, as long as the local surface orientation, the normal vector, is available at every surface point. Local shape features can be used to find putative point correspondences between the models due to their ability to handle noisy and incomplete data. However, this correspondence set is usually contaminated by outliers in practical scenarios, which has led to many past contributions based on robust detectors such as the Hough transform or RANSAC. The key insight of our work is that a single correspondence between oriented points on the two models is constrained to cast votes in a 1 DoF rotational subgroup of the full group of poses, SE(3). Kernel density estimation allows combining the set of votes efficiently to determine a full 6 DoF candidate pose between the models. This modal pose with the highest density is stable under challenging conditions, such as noise, clutter, and occlusions, and provides the output estimate of our method. We first analyze the robustness of our method in relation to noise and show that it handles high outlier rates much better than RANSAC for the task of 6 DoF pose estimation. We then apply our method to four state of the art data sets for 3D object recognition that contain occluded and cluttered scenes. Our method achieves perfect recall on two LIDAR data sets and outperforms competing methods on two RGB-D data sets, thus setting a new standard for general 3D object recognition using point cloud data.

##### Abstract (translated by Google)
只要局部表面方向（法向矢量）在每个表面点都可用，就可以在两个三维形状之间关联高度受限的相对6个DoF姿态的子集。局部形状特征可以用来找出假定的模型之间的点对应，因为它们能够处理嘈杂和不完整的数据。然而，这种通信集通常在实际情况下被异常值所污染，这导致了许多基于鲁棒检测器（如霍夫变换或RANSAC）的贡献。我们的工作的关键洞察是两个模型上的定向点之间的单一对应关系被限制在整组姿态的一个DoF旋转子群SE（3）中投票。核密度估计允许有效地组合该组投票以确定模型之间的完整的6DF候选姿态。在噪声，杂波和遮挡等具有挑战性的条件下，这种密度最高的模态姿态是稳定的，并提供了我们方法的输出估计。我们首先分析我们的方法在噪声方面的鲁棒性，并且表明它在6个DoF姿态估计的任务中比RANSAC处理高得多的离群率。然后，我们将我们的方法应用于包含遮挡和杂乱场景的四个最先进的3D数据集。我们的方法在两个LIDAR数据集上实现了完美的召回，并且在两个RGB-D数据集上胜过了竞争的方法，从而为使用点云数据的一般3D对象识别设定了新的标准。

##### URL
[https://arxiv.org/abs/1709.02142](https://arxiv.org/abs/1709.02142)

##### PDF
[https://arxiv.org/pdf/1709.02142](https://arxiv.org/pdf/1709.02142)

