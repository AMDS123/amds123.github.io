---
layout: post
title: "Hierarchical Motion Consistency Constraint for Efficient Geometrical Verification in UAV Image Matching"
date: 2018-01-12 09:15:29
categories: arXiv_CV
tags: arXiv_CV Relation
author: San Jiang, Wanshou Jiang
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a strategy for efficient geometrical verification in unmanned aerial vehicle (UAV) image matching. First, considering the complex transformation model between correspondence set in the image-space, feature points of initial candidate matches are projected onto an elevation plane in the object-space, with assistant of UAV flight control data and camera mounting angles. Spatial relationships are simplified as a 2D-translation in which a motion establishes the relation of two correspondence points. Second, a hierarchical motion consistency constraint, termed HMCC, is designed to eliminate outliers from initial candidate matches, which includes three major steps, namely the global direction consistency constraint, the local direction-change consistency constraint and the global length consistency constraint. To cope with scenarios with high outlier ratios, the HMCC is achieved by using a voting scheme. Finally, an efficient geometrical verification strategy is proposed by using the HMCC as a pre-processing step to increase inlier ratios before the consequent application of the basic RANSAC algorithm. The performance of the proposed strategy is verified through comprehensive comparison and analysis by using real UAV datasets captured with different photogrammetric systems. Experimental results demonstrate that the generated motions have noticeable separation ability, and the HMCC-RANSAC algorithm can efficiently eliminate outliers based on the motion consistency constraint, with a speedup ratio reaching to 6 for oblique UAV images. Even though the completeness sacrifice of approximately 7 percent of points is observed from image orientation tests, competitive orientation accuracy is achieved from all used datasets. For geometrical verification of both nadir and oblique UAV images, the proposed method can be a more efficient solution.

##### Abstract (translated by Google)
本文提出了一种在无人机（UAV）图像匹配中进行高效几何验证的策略。首先考虑图像空间中对应集之间复杂的变换模型，将初始候选匹配的特征点投影到目标空间的高程平面上，并辅以无人机的飞行控制数据和摄像机安装角度。空间关系被简化为2D翻译，其中运动建立两个对应点的关系。其次，设计了层次运动一致性约束HMCC，从初始候选匹配中去除异常值，包括全局方向一致性约束，局部方向变化一致性约束和全局长度一致性约束三个主要步骤。为了应对具有高偏离率的情况，HMCC通过使用投票方案来实现。最后，在基本RANSAC算法的应用之前，通过使用HMCC作为预处理步骤来增加Inlier比率，提出了一种有效的几何验证策略。通过使用不同摄影测量系统拍摄的真实无人机数据集进行综合比较和分析，验证了所提出策略的性能。实验结果表明，所生成的运动具有明显的分离能力，HMCC-RANSAC算法能够根据运动一致性约束条件有效地消除异常值，对于倾斜的无人机图像，加速比达到6。尽管从图像定向测试中观察到大约百分之七的完整性牺牲，但是从所有使用的数据集中可以获得竞争定位精度。对于最低点和倾斜无人机图像的几何验证，所提出的方法可以是更有效的解决方案。

##### URL
[http://arxiv.org/abs/1801.04096](http://arxiv.org/abs/1801.04096)

##### PDF
[http://arxiv.org/pdf/1801.04096](http://arxiv.org/pdf/1801.04096)

