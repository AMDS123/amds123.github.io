---
layout: post
title: "L2GSCI: Local to Global Seam Cutting and Integrating for Accurate Face Contour Extraction"
date: 2017-03-05 15:06:28
categories: arXiv_CV
tags: arXiv_CV Sparse Face
author: Yongwei Nie, Xu Cao, Chengjiang Long, Ping Li, Guiqing Li
mathjax: true
---

* content
{:toc}

##### Abstract
Current face alignment algorithms can robustly find a set of landmarks along face contour. However, the landmarks are sparse and lack curve details, especially in chin and cheek areas where a lot of concave-convex bending information exists. In this paper, we propose a local to global seam cutting and integrating algorithm (L2GSCI) to extract continuous and accurate face contour. Our method works in three steps with the help of a rough initial curve. First, we sample small and overlapped squares along the initial curve. Second, the seam cutting part of L2GSCI extracts a local seam in each square region. Finally, the seam integrating part of L2GSCI connects all the redundant seams together to form a continuous and complete face curve. Overall, the proposed method is much more straightforward than existing face alignment algorithms, but can achieve pixel-level continuous face curves rather than discrete and sparse landmarks. Moreover, experiments on two face benchmark datasets (i.e., LFPW and HELEN) show that our method can precisely reveal concave-convex bending details of face contours, which has significantly improved the performance when compared with the state-ofthe- art face alignment approaches.

##### Abstract (translated by Google)
当前的人脸对准算法可以沿着人脸轮廓鲁棒地找到一组地标。但是地标比较稀疏，缺乏曲线细节，特别是在存在很多凹凸弯曲信息的下巴和脸颊区域。在本文中，我们提出了一种局部到全局的切割和积分算法（L2GSCI）来提取连续和精确的人脸轮廓。我们的方法在三个步骤的帮助下粗略的初始曲线。首先，我们沿着初始曲线对小的和重叠的方块进行采样。其次，L2GSCI的切缝部分在每个正方形区域提取局部接缝。最后，L2GSCI的接缝集成部分将所有冗余接缝连接在一起，形成一个连续而完整的面部曲线。总体而言，所提出的方法比现有的人脸对准算法更直接，但是可以实现像素级连续人脸曲线而不是离散和稀疏的标记。而且，对两个人脸基准数据集（即LFPW和HELEN）的实验表明，我们的方法可以精确地揭示人脸轮廓的凹凸弯曲细节，与现有技术的面部对齐方法相比，其性能显着提高。

##### URL
[https://arxiv.org/abs/1703.01605](https://arxiv.org/abs/1703.01605)

##### PDF
[https://arxiv.org/pdf/1703.01605](https://arxiv.org/pdf/1703.01605)

