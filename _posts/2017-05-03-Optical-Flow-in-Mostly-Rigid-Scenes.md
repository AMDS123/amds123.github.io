---
layout: post
title: "Optical Flow in Mostly Rigid Scenes"
date: 2017-05-03 10:48:21
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Jonas Wulff, Laura Sevilla-Lara, Michael J. Black
mathjax: true
---

* content
{:toc}

##### Abstract
The optical flow of natural scenes is a combination of the motion of the observer and the independent motion of objects. Existing algorithms typically focus on either recovering motion and structure under the assumption of a purely static world or optical flow for general unconstrained scenes. We combine these approaches in an optical flow algorithm that estimates an explicit segmentation of moving objects from appearance and physical constraints. In static regions we take advantage of strong constraints to jointly estimate the camera motion and the 3D structure of the scene over multiple frames. This allows us to also regularize the structure instead of the motion. Our formulation uses a Plane+Parallax framework, which works even under small baselines, and reduces the motion estimation to a one-dimensional search problem, resulting in more accurate estimation. In moving regions the flow is treated as unconstrained, and computed with an existing optical flow method. The resulting Mostly-Rigid Flow (MR-Flow) method achieves state-of-the-art results on both the MPI-Sintel and KITTI-2015 benchmarks.

##### Abstract (translated by Google)
自然场景的光流是观察者运动和物体独立运动的结合。现有的算法通常集中在假设纯静态世界或假设一般无约束场景时的光流恢复运动和结构。我们将这些方法结合在光流算法中，该算法根据外观和物理约束来估计移动对象的显式分割。在静态区域中，我们利用强约束条件来联合估计多帧中的相机运动和场景的三维结构。这使我们也可以调整结构而不是运动。我们的公式使用平面+视差框架，即使在小的基线下也可以工作，并将运动估计减少到一维搜索问题，从而导致更精确的估计。在移动区域，流动被视为无约束的，并且用现有的光流法来计算。由此产生的大量刚性流（MR-Flow）方法在MPI-Sintel和KITTI-2015基准测试中均达到了最新的结果。

##### URL
[https://arxiv.org/abs/1705.01352](https://arxiv.org/abs/1705.01352)

##### PDF
[https://arxiv.org/pdf/1705.01352](https://arxiv.org/pdf/1705.01352)

