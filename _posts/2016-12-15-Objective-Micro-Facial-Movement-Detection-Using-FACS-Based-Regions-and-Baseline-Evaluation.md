---
layout: post
title: "Objective Micro-Facial Movement Detection Using FACS-Based Regions and Baseline Evaluation"
date: 2016-12-15 12:15:36
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face Detection
author: Adrian K. Davison, Cliff Lansley, Choon Ching Ng, Kevin Tan, Moi Hoon Yap
mathjax: true
---

* content
{:toc}

##### Abstract
Micro-facial expressions are regarded as an important human behavioural event that can highlight emotional deception. Spotting these movements is difficult for humans and machines, however research into using computer vision to detect subtle facial expressions is growing in popularity. This paper proposes an individualised baseline micro-movement detection method using 3D Histogram of Oriented Gradients (3D HOG) temporal difference method. We define a face template consisting of 26 regions based on the Facial Action Coding System (FACS). We extract the temporal features of each region using 3D HOG. Then, we use Chi-square distance to find subtle facial motion in the local regions. Finally, an automatic peak detector is used to detect micro-movements above the newly proposed adaptive baseline threshold. The performance is validated on two FACS coded datasets: SAMM and CASME II. This objective method focuses on the movement of the 26 face regions. When comparing with the ground truth, the best result was an AUC of 0.7512 and 0.7261 on SAMM and CASME II, respectively. The results show that 3D HOG outperformed for micro-movement detection, compared to state-of-the-art feature representations: Local Binary Patterns in Three Orthogonal Planes and Histograms of Oriented Optical Flow.

##### Abstract (translated by Google)
微面部表情被认为是一个重要的人类行为事件，可以突出情绪欺骗。发现这些动作对于人类和机器来说是困难的，但是使用计算机视觉来检测细微的面部表情的研究正在变得越来越流行。本文提出了一种基于三维直方图（3D HOG）时间差分方法的个体化基线微动检测方法。我们基于面部动作编码系统（FACS）定义了由26个区域组成的面部模板。我们使用3D HOG提取每个区域的时间特征。然后，我们使用卡方距离在本地区域发现微妙的面部运动。最后，使用自动峰值检测器来检测在新提出的自适应基线阈值之上的微移动。性能通过两个FACS编码数据集进行验证：SAMM和CASME II。这个客观的方法侧重于26个人脸区域的移动。与实际情况相比，SAMM和CASME II的最佳结果分别为0.7512和0.7261。结果表明，三维HOG优于微动检测，相比，最先进的特征表示：局部二进制模式在三个正交平面和直方图的面向光流。

##### URL
[https://arxiv.org/abs/1612.05038](https://arxiv.org/abs/1612.05038)

##### PDF
[https://arxiv.org/pdf/1612.05038](https://arxiv.org/pdf/1612.05038)

