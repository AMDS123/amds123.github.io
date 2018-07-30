---
layout: post
title: "A Novel Geometry-based Algorithm for Robust Grasping in Extreme Clutter Environment"
date: 2018-07-27 12:18:20
categories: arXiv_RO
tags: arXiv_RO Knowledge Face Detection
author: Olyvia Kundu, Swagat Kumar
mathjax: true
---

* content
{:toc}

##### Abstract
This paper looks into the problem of grasping unknown objects in a cluttered environment using 3D point cloud data obtained from a range or an RGBD sensor. The objective is to identify graspable regions and detect suitable grasp poses from a single view, possibly, partial 3D point cloud without any apriori knowledge of the object geometry. The problem is solved in two steps: (1) identifying and segmenting various object surfaces and, (2) searching for suitable grasping handles on these surfaces by applying geometric constraints of the physical gripper. The first step is solved by using a modified version of region growing algorithm that uses a pair of thresholds for smoothness constraint on local surface normals to find natural boundaries of object surfaces. In this process, a novel concept of edge point is introduced that allows us to segment between different surfaces of the same object. The second step is solved by converting a 6D pose detection problem into a 1D linear search problem by projecting 3D cloud points onto the principal axes of the object surface. The graspable handles are then localized by applying physical constraints of the gripper. The resulting method allows us to grasp all kinds of objects including rectangular or box-type objects with flat surfaces which have been difficult so far to deal with in the grasping literature. The proposed method is simple and can be implemented in real-time and does not require any off-line training phase for finding these affordances. The improvements achieved is demonstrated through comparison with another state-of-the-art grasping algorithm on various publicly-available and self-created datasets.

##### Abstract (translated by Google)
本文研究了使用从范围或RGBD传感器获得的3D点云数据在杂乱环境中抓取未知对象的问题。目的是识别可抓握区域并从单个视图（可能是部分3D点云）中检测合适的抓握姿势，而无需对对象几何形状进行任何先验知识。该问题分两步解决：（1）识别和分割各种物体表面，以及（2）通过应用物理抓取器的几何约束在这些表面上搜索合适的抓握手柄。通过使用区域生长算法的修改版本来解决第一步，该算法使用一对阈值来对局部表面法线进行平滑约束以找到物体表面的自然边界。在这个过程中，引入了一个新的边缘点概念，它允许我们在同一个对象的不同表面之间进行分割。通过将3D浊点投影到物体表面的主轴上，将6D姿势检测问题转换为1D线性搜索问题来解决第二步骤。然后通过应用夹具的物理约束来定位可抓握的手柄。由此产生的方法使我们能够掌握各种物体，包括具有平坦表面的矩形或箱形物体，这些物体迄今为止在抓取文献中难以处理。所提出的方法简单并且可以实时实施，并且不需要任何离线训练阶段来发现这些可供性。通过与各种公开可用和自创建的数据集上的另一种最先进的抓取算法进行比较，证明了所实现的改进。

##### URL
[https://arxiv.org/abs/1807.10548](https://arxiv.org/abs/1807.10548)

##### PDF
[https://arxiv.org/pdf/1807.10548](https://arxiv.org/pdf/1807.10548)

