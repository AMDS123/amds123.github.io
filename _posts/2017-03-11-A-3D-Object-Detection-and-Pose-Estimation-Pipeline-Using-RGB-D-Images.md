---
layout: post
title: "A 3D Object Detection and Pose Estimation Pipeline Using RGB-D Images"
date: 2017-03-11 10:09:02
categories: arXiv_CV
tags: arXiv_CV Object_Detection Pose_Estimation Detection
author: Ruotao He, Juan Rojas, Yisheng Guan
mathjax: true
---

* content
{:toc}

##### Abstract
3D object detection and pose estimation has been studied extensively in recent decades for its potential applications in robotics. However, there still remains challenges when we aim at detecting multiple objects while retaining low false positive rate in cluttered environments. This paper proposes a robust 3D object detection and pose estimation pipeline based on RGB-D images, which can detect multiple objects simultaneously while reducing false positives. Detection begins with template matching and yields a set of template matches. A clustering algorithm then groups templates of similar spatial location and produces multiple-object hypotheses. A scoring function evaluates the hypotheses using their associated templates and non-maximum suppression is adopted to remove duplicate results based on the scores. Finally, a combination of point cloud processing algorithms are used to compute objects' 3D poses. Existing object hypotheses are verified by computing the overlap between model and scene points. Experiments demonstrate that our approach provides competitive results comparable to the state-of-the-arts and can be applied to robot random bin-picking.

##### Abstract (translated by Google)
近几十年来，3D物体检测和姿态估计已经在机器人领域的潜在应用中被广泛研究。然而，当我们的目标是检测多个物体，同时在杂乱的环境中保持低误报率时仍然存在挑战。本文提出了一种基于RGB-D图像的鲁棒性三维物体检测与姿态估计流水线，能够同时检测多个物体，同时减少误报。检测从模板匹配开始，并产生一组模板匹配。聚类算法然后将相似空间位置的模板分组并产生多个对象假设。评分功能使用其关联的模板评估假设，并且基于评分，采用非最大抑制来去除重复的结果。最后，使用点云处理算法的组合来计算对象的3D姿势。现有的对象假设是通过计算模型和场景点之间的重叠来验证的。实验表明，我们的方法提供了与现有技术相媲美的竞争结果，并且可以应用于机器人随机采摘。

##### URL
[https://arxiv.org/abs/1703.03940](https://arxiv.org/abs/1703.03940)

##### PDF
[https://arxiv.org/pdf/1703.03940](https://arxiv.org/pdf/1703.03940)

