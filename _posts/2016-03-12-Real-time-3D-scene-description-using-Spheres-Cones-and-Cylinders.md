---
layout: post
title: "Real-time 3D scene description using Spheres, Cones and Cylinders"
date: 2016-03-12 04:03:46
categories: arXiv_CV
tags: arXiv_CV Tracking
author: Kristiyan Georgiev, Motaz Al-Hami, Rolf Lakaemper
mathjax: true
---

* content
{:toc}

##### Abstract
The paper describes a novel real-time algorithm for finding 3D geometric primitives (cylinders, cones and spheres) from 3D range data. In its core, it performs a fast model fitting with a model update in constant time (O(1)) for each new data point added to the model. We use a three stage approach.The first step inspects 1.5D sub spaces, to find ellipses. The next stage uses these ellipses as input by examining their neighborhood structure to form sets of candidates for the 3D geometric primitives. Finally, candidate ellipses are fitted to the geometric primitives. The complexity for point processing is O(n); additional time of lower order is needed for working on significantly smaller amount of mid-level objects. This allows the approach to process 30 frames per second on Kinect depth data, which suggests this approach as a pre-processing step for 3D real-time higher level tasks in robotics, like tracking or feature based mapping.

##### Abstract (translated by Google)
本文描述了一种新颖的实时算法，用于从3D距离数据中找到3D几何图元（圆柱体，锥体和球体）。在其核心中，为每个添加到模型中的新数据点执行一个在恒定时间（O（1））的模型更新的快速模型拟合。我们使用三阶段的方法。第一步检查1.5D的子空间，找到椭圆。下一阶段使用这些椭圆作为输入，通过检查它们的邻域结构来形成3D几何图元的候选集合。最后，将候选椭圆拟合到几何图元。点处理的复杂度是O（n）;需要额外的更低的时间来处理显着更少数量的中级对象。这使得该方法能够在Kinect深度数据上每秒处理30帧，这表明该方法是机器人3D实时高级任务（如跟踪或基于特征的映射）的预处理步骤。

##### URL
[https://arxiv.org/abs/1603.03856](https://arxiv.org/abs/1603.03856)

##### PDF
[https://arxiv.org/pdf/1603.03856](https://arxiv.org/pdf/1603.03856)

