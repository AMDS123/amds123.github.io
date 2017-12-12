---
layout: post
title: "Using a single RGB frame for real time 3D hand pose estimation in the wild"
date: 2017-12-11 16:16:05
categories: arXiv_CV
tags: arXiv_CV Object_Detection Pose_Estimation Deep_Learning Detection
author: Paschalis Panteleris, Iason Oikonomidis, Antonis Argyros
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method for the real-time estimation of the full 3D pose of one or more human hands using a single commodity RGB camera. Recent work in the area has displayed impressive progress using RGBD input. However, since the introduction of RGBD sensors, there has been little progress for the case of monocular color input. We capitalize on the latest advancements of deep learning, combining them with the power of generative hand pose estimation techniques to achieve real-time monocular 3D hand pose estimation in unrestricted scenarios. More specifically, given an RGB image and the relevant camera calibration information, we employ a state-of-the-art detector to localize hands. Given a crop of a hand in the image, we run the pretrained network of OpenPose for hands to estimate the 2D location of hand joints. Finally, non-linear least-squares minimization fits a 3D model of the hand to the estimated 2D joint positions, recovering the 3D hand pose. Extensive experimental results provide comparison to the state of the art as well as qualitative assessment of the method in the wild.

##### Abstract (translated by Google)
我们提出了一种使用单个商品RGB照相机实时估算一个或多个人手的全3D姿态的方法。近期在该领域的工作使用RGBD输入显示了令人瞩目的进展。然而，自引入RGBD传感器以来，单色输入的情况几乎没有进展。我们利用深度学习的最新进展，将它们与生成性手势估计技术的功能相结合，实现无限制场景下的实时单眼3D手势估计。更具体地说，给定一个RGB图像和相关的摄像机校准信息，我们使用最先进的探测器来定位手。鉴于图像中的一个手，我们运行OpenPose的预训练网络来手估计手关节的二维位置。最后，非线性最小平方最小化将手的3D模型拟合到估计的2D关节位置，恢复3D手姿态。广泛的实验结果提供了对现有技术的比较以及在野外方法的定性评估。

##### URL
[http://arxiv.org/abs/1712.03866](http://arxiv.org/abs/1712.03866)

##### PDF
[http://arxiv.org/pdf/1712.03866](http://arxiv.org/pdf/1712.03866)

