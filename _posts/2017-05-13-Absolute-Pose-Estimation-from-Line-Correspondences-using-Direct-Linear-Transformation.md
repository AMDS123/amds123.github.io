---
layout: post
title: "Absolute Pose Estimation from Line Correspondences using Direct Linear Transformation"
date: 2017-05-13 10:38:02
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation
author: Bronislav Přibyl, Pavel Zemčík, Martin Čadík
mathjax: true
---

* content
{:toc}

##### Abstract
This work is concerned with camera pose estimation from correspondences of 3D/2D lines, i. e. with the Perspective-n-Line (PnL) problem. We focus on large line sets, which can be efficiently solved by methods using linear formulation of PnL. We propose a novel method "DLT-Combined-Lines" based on the Direct Linear Transformation (DLT) algorithm, which benefits from a new combination of two existing DLT methods for pose estimation. The method represents 2D structure by lines, and 3D structure by both points and lines. The redundant 3D information reduces the minimum required line correspondences to 5. A cornerstone of the method is a combined projection matri xestimated by the DLT algorithm. It contains multiple estimates of camera rotation and translation, which can be recovered after enforcing constraints of the matrix. Multiplicity of the estimates is exploited to improve the accuracy of the proposed method. For large line sets (10 and more), the method is comparable to the state-of-theart in accuracy of orientation estimation. It achieves state-of-the-art accuracy in estimation of camera position and it yields the smallest reprojection error under strong image noise. The method achieves top-3 results on real world data. The proposed method is also highly computationally effective, estimating the pose of 1000 lines in 12 ms on a desktop computer.

##### Abstract (translated by Google)
这项工作涉及3D / 2D线对应的相机姿态估计，即与透视n线（PnL）问题。我们专注于大型线路集，这可以通过使用PnL的线性公式的方法有效地解决。我们提出了一种基于直接线性变换（DLT）算法的“DLT-Combined-Lines”新方法，该方法受益于两种现有的DLT方法的新组合，用于姿态估计。该方法用线表示二维结构，用点和线表示三维结构。冗余3D信息将所需的最小行对应关系减少到5个。该方法的基石是由DLT算法估算的组合投影矩阵。它包含多个相机旋转和平移的估计值，可以在强制执行矩阵的约束后恢复。多样性的估计被利用来提高所提出的方法的准确性。对于大型线路集（10个或更多），该方法与定位估计精确度的现状相当。它在照相机位置估计方面达到了最新的精确度，并在强烈的图像噪声下产生最小的重投影误差。该方法实现了真实世界数据的前3名。所提出的方法在计算上也是高度有效的，在台式计算机上在12ms内估计1000行的姿态。

##### URL
[https://arxiv.org/abs/1608.06891](https://arxiv.org/abs/1608.06891)

##### PDF
[https://arxiv.org/pdf/1608.06891](https://arxiv.org/pdf/1608.06891)

