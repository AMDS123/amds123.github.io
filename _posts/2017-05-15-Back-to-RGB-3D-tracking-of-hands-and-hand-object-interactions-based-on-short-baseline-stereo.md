---
layout: post
title: "Back to RGB: 3D tracking of hands and hand-object interactions based on short-baseline stereo"
date: 2017-05-15 15:38:56
categories: arXiv_CV
tags: arXiv_CV Tracking Optimization Quantitative
author: Paschalis Panteleris (1), Antonis Argyros (1 and 2) ((1) Institute of Computer Science, FORTH, (2) Computer Science Department, University of Crete)
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel solution to the problem of 3D tracking of the articulated motion of human hand(s), possibly in interaction with other objects. The vast majority of contemporary relevant work capitalizes on depth information provided by RGBD cameras. In this work, we show that accurate and efficient 3D hand tracking is possible, even for the case of RGB stereo. A straightforward approach for solving the problem based on such input would be to first recover depth and then apply a state of the art depth-based 3D hand tracking method. Unfortunately, this does not work well in practice because the stereo-based, dense 3D reconstruction of hands is far less accurate than the one obtained by RGBD cameras. Our approach bypasses 3D reconstruction and follows a completely different route: 3D hand tracking is formulated as an optimization problem whose solution is the hand configuration that maximizes the color consistency between the two views of the hand. We demonstrate the applicability of our method for real time tracking of a single hand, of a hand manipulating an object and of two interacting hands. The method has been evaluated quantitatively on standard datasets and in comparison to relevant, state of the art RGBD-based approaches. The obtained results demonstrate that the proposed stereo-based method performs equally well to its RGBD-based competitors, and in some cases, it even outperforms them.

##### Abstract (translated by Google)
我们提出了一种新的解决方案，可以在与其他物体相互作用的情况下对人手的关节运动进行三维跟踪。绝大多数当代相关工作利用RGBD相机提供的深度信息。在这项工作中，我们表明，即使对于RGB立体声的情况，精确和高效的3D手部跟踪也是可能的。基于这种输入来解决问题的直接方法是首先恢复深度，然后应用最先进的基于深度的3D手部跟踪方法。不幸的是，这在实际中效果不佳，因为基于立体的，密集的3D重建手的准确性远不如RGBD相机所获得的重建准确。我们的方法绕过三维重建，并遵循完全不同的路线：三维手部跟踪被制定为一个优化问题，其解决方案是手部配置，最大限度地提高手部两个视图之间的颜色一致性。我们证明了我们的方法实时跟踪一只手，一只手操纵一个物体和两只相互作用的手的适用性。已经在标准数据集上定量评估了该方法，并与相关的现有技术的基于RGBD的方法进行了比较。所获得的结果表明，所提出的基于立体的方法对于其基于RGBD的竞争者表现同样好，在某些情况下甚至胜过它们。

##### URL
[https://arxiv.org/abs/1705.05301](https://arxiv.org/abs/1705.05301)

##### PDF
[https://arxiv.org/pdf/1705.05301](https://arxiv.org/pdf/1705.05301)

