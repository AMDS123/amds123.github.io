---
layout: post
title: "GPU based Parallel Optimization for Real Time Panoramic Video Stitching"
date: 2018-10-22 07:56:26
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Chengyao Du, Jingling Yuan, Jiansheng Dong, Lin Li, Mincheng Chen, Tao Li
mathjax: true
---

* content
{:toc}

##### Abstract
Panoramic video is a sort of video recorded at the same point of view to record the full scene. With the development of video surveillance and the requirement for 3D converged video surveillance in smart cities, CPU and GPU are required to possess strong processing abilities to make panoramic video. The traditional panoramic products depend on post processing, which results in high power consumption, low stability and unsatisfying performance in real time. In order to solve these problems,we propose a real-time panoramic video stitching framework.The framework we propose mainly consists of three algorithms, LORB image feature extraction algorithm, feature point matching algorithm based on LSH and GPU parallel video stitching algorithm based on CUDA.The experiment results show that the algorithm mentioned can improve the performance in the stages of feature extraction of images stitching and matching, the running speed of which is 11 times than that of the traditional ORB algorithm and 639 times than that of the traditional SIFT algorithm. Based on analyzing the GPU resources occupancy rate of each resolution image stitching, we further propose a stream parallel strategy to maximize the utilization of GPU resources. Compared with the L-ORB algorithm, the efficiency of this strategy is improved by 1.6-2.5 times, and it can make full use of GPU resources. The performance of the system accomplished in the paper is 29.2 times than that of the former embedded one, while the power dissipation is reduced to 10W.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.03988](http://arxiv.org/abs/1810.03988)

##### PDF
[http://arxiv.org/pdf/1810.03988](http://arxiv.org/pdf/1810.03988)

