---
layout: post
title: "Object Tracking based on Quantum Particle Swarm Optimization"
date: 2017-05-24 10:29:45
categories: arXiv_CV
tags: arXiv_CV Tracking Object_Tracking Optimization
author: Rajesh Misra, Kumar S. Ray
mathjax: true
---

* content
{:toc}

##### Abstract
In Computer Vision domain, moving Object Tracking considered as one of the toughest problem.As there so many factors associated like illumination of light, noise, occlusion, sudden start and stop of moving object, shading which makes tracking even harder problem not only for dynamic background but also for static background.In this paper we present a new object tracking algorithm based on Dominant points on tracked object using Quantum particle swarm optimization (QPSO) which is a new different version of PSO based on Quantum theory. The novelty in our approach is that it can be successfully applicable in variable background as well as static background and application of quantum PSO makes the algorithm runs lot faster where other basic PSO algorithm failed to do so due to heavy computation.In our approach firstly dominants points of tracked objects detected, then a group of particles form a swarm are initialized randomly over the image search space and then start searching the curvature connected between two consecutive dominant points until they satisfy fitness criteria. Obviously it is a Multi-Swarm approach as there are multiple dominant points, as they moves, the curvature moves and the curvature movement is tracked by the swarm throughout the video and eventually when the swarm reaches optimal solution , a bounding box drawn based on particles final position.Experimental results demonstrate this proposed QPSO based method work efficiently and effectively in visual object tracking in both dynamic and static environments and run time shows that it runs closely 90% faster than basic PSO.in our approach we also apply parallelism using MatLab Parfor command to show how very less number of iteration and swarm size will enable us to successfully track object.

##### Abstract (translated by Google)
在计算机视觉领域，移动物体跟踪被认为是最棘手的问题之一。由于光照，噪声，遮挡，移动物体的突然启动和停止等因素相关联，使得跟踪更难的问题本文提出了一种基于量子理论的基于量子粒子群优化算法（QPSO）的跟踪目标跟踪算法，该算法是基于量子理论的新型PSO算法。我们的方法的新颖之处在于它可以成功应用于变量背景以及静态背景和量子粒子群算法的应用，使得算法在其他基本粒子群算法由于计算量大而无法实现的情况下运行速度更快。在我们的方法中，然后在图像搜索空间随机初始化一组粒子形成一个群体，然后开始搜索连续两个主要点之间的曲率，直到它们满足适应度标准。很显然，这是一种多群体方法，因为有多个主导点，当它们移动时，曲率移动，曲率运动在整个视频中被群体跟踪，并且最终当群体达到最优解时，基于粒子绘制的边界框实验结果表明，本文提出的基于QPSO的方法在动态和静态环境下的视觉对象跟踪方面都能够高效有效地工作，运行时间表明其运行速度比基本PSO快近90％。在我们的方法中，我们也使用MatLab Parfor命令来显示迭代次数和群体大小将使我们能够成功跟踪对象。

##### URL
[https://arxiv.org/abs/1707.05228](https://arxiv.org/abs/1707.05228)

##### PDF
[https://arxiv.org/pdf/1707.05228](https://arxiv.org/pdf/1707.05228)

