---
layout: post
title: "Dynamic Body VSLAM with Semantic Constraints"
date: 2015-04-27 20:30:04
categories: arXiv_CV
tags: arXiv_CV Segmentation Tracking Optimization SLAM
author: N. Dinesh Reddy, Prateek Singhal, Visesh Chari, K. Madhava Krishna
mathjax: true
---

* content
{:toc}

##### Abstract
Image based reconstruction of urban environments is a challenging problem that deals with optimization of large number of variables, and has several sources of errors like the presence of dynamic objects. Since most large scale approaches make the assumption of observing static scenes, dynamic objects are relegated to the noise modeling section of such systems. This is an approach of convenience since the RANSAC based framework used to compute most multiview geometric quantities for static scenes naturally confine dynamic objects to the class of outlier measurements. However, reconstructing dynamic objects along with the static environment helps us get a complete picture of an urban environment. Such understanding can then be used for important robotic tasks like path planning for autonomous navigation, obstacle tracking and avoidance, and other areas. In this paper, we propose a system for robust SLAM that works in both static and dynamic environments. To overcome the challenge of dynamic objects in the scene, we propose a new model to incorporate semantic constraints into the reconstruction algorithm. While some of these constraints are based on multi-layered dense CRFs trained over appearance as well as motion cues, other proposed constraints can be expressed as additional terms in the bundle adjustment optimization process that does iterative refinement of 3D structure and camera / object motion trajectories. We show results on the challenging KITTI urban dataset for accuracy of motion segmentation and reconstruction of the trajectory and shape of moving objects relative to ground truth. We are able to show average relative error reduction by a significant amount for moving object trajectory reconstruction relative to state-of-the-art methods like VISO 2, as well as standard bundle adjustment algorithms.

##### Abstract (translated by Google)
基于图像的城市环境重建是一个具有挑战性的问题，它处理大量变量的优化问题，并且存在像动态对象存在这样的错误源。由于大多数大规模的方法都是假设观察静态场景，所以动态对象被分解到这种系统的噪声建模部分。这是一种方便的方法，因为用于计算静态场景的大多数视点几何量的基于RANSAC的框架自然地将动态对象限制在异常值测量类别中。然而，随着静态环境重建动态物体，可以帮助我们了解城市环境的全貌。这样的理解可以用于重要的机器人任务，如自主导航的路径规划，障碍物追踪和避免等领域。在本文中，我们提出了一个适用于静态和动态环境的稳健SLAM系统。为了克服场景中动态物体的挑战，我们提出了一个新的模型，将语义约束融合到重建算法中。尽管这些约束中的一些是基于多层密集CRF在外观和运动线索上训练的，但是其他提出的约束可以被表达为束调整优化过程中的附加项，该过程对3D结构和相机/物体运动轨迹进行迭代细化。我们在具有挑战性的KITTI城市数据集上显示运动分割的准确性和移动物体相对于地面真实的轨迹和形状的重建的结果。相对于VISO 2等最先进的方法，以及标准的束调整算法，我们能够显示平均相对误差减少量相当大的移动物体轨迹重建。

##### URL
[https://arxiv.org/abs/1504.07269](https://arxiv.org/abs/1504.07269)

##### PDF
[https://arxiv.org/pdf/1504.07269](https://arxiv.org/pdf/1504.07269)

