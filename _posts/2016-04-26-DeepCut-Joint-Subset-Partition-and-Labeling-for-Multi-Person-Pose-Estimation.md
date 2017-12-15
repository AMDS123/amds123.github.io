---
layout: post
title: "DeepCut: Joint Subset Partition and Labeling for Multi Person Pose Estimation"
date: 2016-04-26 04:26:29
categories: arXiv_CV
tags: arXiv_CV Object_Detection Pose_Estimation Detection
author: Leonid Pishchulin, Eldar Insafutdinov, Siyu Tang, Bjoern Andres, Mykhaylo Andriluka, Peter Gehler, Bernt Schiele
mathjax: true
---

* content
{:toc}

##### Abstract
This paper considers the task of articulated human pose estimation of multiple people in real world images. We propose an approach that jointly solves the tasks of detection and pose estimation: it infers the number of persons in a scene, identifies occluded body parts, and disambiguates body parts between people in close proximity of each other. This joint formulation is in contrast to previous strategies, that address the problem by first detecting people and subsequently estimating their body pose. We propose a partitioning and labeling formulation of a set of body-part hypotheses generated with CNN-based part detectors. Our formulation, an instance of an integer linear program, implicitly performs non-maximum suppression on the set of part candidates and groups them to form configurations of body parts respecting geometric and appearance constraints. Experiments on four different datasets demonstrate state-of-the-art results for both single person and multi person pose estimation. Models and code available at this http URL

##### Abstract (translated by Google)
本文考虑了多人在现实世界图像中的人类姿态估计的任务。我们提出了一种共同解决检测和姿态估计任务的方法：它推断场景中的人数，识别被遮挡的身体部位，并且消除彼此靠近的人之间的身体部位。这个联合表述与以前的策略形成对比，通过首先检测人员并随后估计他们的身体姿势来解决该问题。我们提出了一套用基于CNN的部分检测器生成的一组身体部分假设的分割和标记公式。我们的公式是整数线性程序的一个实例，隐式地对候选部件集合执行非最大抑制，并将它们分组以形成关于几何和外观约束的身体部位的配置。四个不同数据集上的实验证明了单人和多人姿态估计的最新结果。这个http URL提供的模型和代码

##### URL
[https://arxiv.org/abs/1511.06645](https://arxiv.org/abs/1511.06645)

##### PDF
[https://arxiv.org/pdf/1511.06645](https://arxiv.org/pdf/1511.06645)

