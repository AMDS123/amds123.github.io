---
layout: post
title: "Incremental Reconstruction of Urban Environments by Edge-Points Delaunay Triangulation"
date: 2016-04-27 13:11:03
categories: arXiv_CV
tags: arXiv_CV Sparse Face Survey
author: Andrea Romanoni, Matteo Matteucci
mathjax: true
---

* content
{:toc}

##### Abstract
Urban reconstruction from a video captured by a surveying vehicle constitutes a core module of automated mapping. When computational power represents a limited resource and, a detailed map is not the primary goal, the reconstruction can be performed incrementally, from a monocular video, carving a 3D Delaunay triangulation of sparse points; this allows online incremental mapping for tasks such as traversability analysis or obstacle avoidance. To exploit the sharp edges of urban landscape, we propose to use a Delaunay triangulation of Edge-Points, which are the 3D points corresponding to image edges. These points constrain the edges of the 3D Delaunay triangulation to real-world edges. Besides the use of the Edge-Points, a second contribution of this paper is the Inverse Cone Heuristic that preemptively avoids the creation of artifacts in the reconstructed manifold surface. We force the reconstruction of a manifold surface since it makes it possible to apply computer graphics or photometric refinement algorithms to the output mesh. We evaluated our approach on four real sequences of the public available KITTI dataset by comparing the incremental reconstruction against Velodyne measurements.

##### Abstract (translated by Google)
从测绘车辆拍摄的视频中进行城市重建是自动测绘的核心模块。当计算能力代表有限的资源时，详细的地图不是主要的目标，重建可以从单眼视频渐进地进行，雕刻稀疏点的3D Delaunay三角剖分;这允许在线增量映射用于诸如遍历分析或障碍避免的任务。为了利用城市景观的锐利边缘，我们建议使用边缘点的Delaunay三角剖分，这是与图像边缘相对应的3D点。这些点将3D Delaunay三角剖分的边缘约束为真实的边缘。除了使用边缘点之外，本文的第二个贡献是逆锥体启发式，它抢先避免了在重构流形表面中产生伪影。我们强制重构一个流形表面，因为它可以将计算机图形或光度细化算法应用到输出网格。我们通过比较增量重构和Velodyne测量来评估我们的方法在公开可用的KITTI数据集的四个实际序列上。

##### URL
[https://arxiv.org/abs/1604.06232](https://arxiv.org/abs/1604.06232)

##### PDF
[https://arxiv.org/pdf/1604.06232](https://arxiv.org/pdf/1604.06232)

