---
layout: post
title: "Planning Safe Paths through Hazardous Environments"
date: 2018-03-02 00:00:53
categories: arXiv_RO
tags: arXiv_RO Survey
author: Chris Denniston, Thomas R. Krogstad, Stephanie Kemna, Gaurav S. Sukhatme
mathjax: true
---

* content
{:toc}

##### Abstract
Autonomous underwater vehicles (AUVs) are robotic platforms that are commonly used to map the sea floor, for example for benthic surveys or for naval mine countermeasures (MCM) operations. AUVs create an acoustic image of the survey area, such that objects on the seabed can be identified and, in the case of MCM, mines can be found and disposed of. The common method for creating such seabed maps is to run a lawnmower survey, which is a standard method in coverage path planning. We are interested in exploring alternate techniques for surveying areas of interest, in order to reduce mission time or assess feasible actions, such as finding a safe path through a hazardous region. In this paper, we use Gaussian Process regression to build models of seabed complexity data, obtained through lawnmower surveys. We evaluate several commonly used kernels to assess their modeling performance, which includes modeling discontinuities in the data. Our results show that an additive Mat\'ern kernel is most suitable for modeling seabed complexity data. On top of the GP model, we use adaptations of two standard path planning methods, A* and RRT*, to find safe paths through the modeled areas. We evaluate the planned paths and also run a vehicle dynamics simulator to assess potential performance by a marine vessel.

##### Abstract (translated by Google)
自治水下航行器（AUV）是通常用于绘制海底地图的机器人平台，例如用于海底勘测或海军地雷对策（MCM）作业。 AUV创建勘测区域的声学图像，以便可以识别海底物体，并且在MCM的情况下，可以找到并处理地雷。创建这种海底地图的常用方法是进行割草机调查，这是覆盖率路径规划的一种标准方法。我们有兴趣探索勘测感兴趣区域的替代技术，以减少任务时间或评估可行的行动，例如通过危险区域寻找安全通道。在本文中，我们使用高斯过程回归来建立通过割草机调查获得的海床复杂性数据模型。我们评估几种常用的内核来评估它们的建模性能，其中包括建模数据中的不连续性。我们的研究结果表明，Mat'ern内核是最适合海底复杂数据建模的。在GP模型之上，我们使用两种标准路径规划方法（A *和RRT *）的修改来查找通过建模区域的安全路径。我们评估计划的路径并运行车辆动态模拟器来评估船舶的潜在性能。

##### URL
[http://arxiv.org/abs/1803.00664](http://arxiv.org/abs/1803.00664)

##### PDF
[http://arxiv.org/pdf/1803.00664](http://arxiv.org/pdf/1803.00664)

