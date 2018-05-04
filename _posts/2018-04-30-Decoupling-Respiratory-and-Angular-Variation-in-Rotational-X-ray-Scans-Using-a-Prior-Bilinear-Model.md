---
layout: post
title: "Decoupling Respiratory and Angular Variation in Rotational X-ray Scans Using a Prior Bilinear Model"
date: 2018-04-30 14:26:15
categories: arXiv_CV
tags: arXiv_CV Knowledge
author: Tobias Geimer, Paul Keall, Katharina Breininger, Vincent Caillet, Michelle Dunbar, Christoph Bert, Andreas Maier
mathjax: true
---

* content
{:toc}

##### Abstract
Data-driven respiratory signal extraction from rotational X-ray scans has always been challenging due to angular effects overlapping with respiration-induced change in the scene. In the context of motion modelling their main drawback is the fact that most of these methods only extract a 1D signal, that, at best, can be decomposed into amplitude and phase. In this paper, we use the linearity of the Radon operator to propose a bilinear model based on a prior 4D scan to separate angular and respiratory variation. Out-of-sample extension is enhanced by a B-spline interpolation using prior knowledge about the trajectory angle to extract respiratory feature weights independent of the acquisition angle. Though the prerequisite of a prior 4D scan seems steep, our proposed application of respiratory motion estimation in radiation therapy usually meets this requirement. We test our approach on DRRs of a patient's 4D CT in a leave-one-out manner and achieve a mean estimation error of 5.2% in the gray values for previously unseen viewing angles.

##### Abstract (translated by Google)
由旋转X射线扫描提取的数据驱动的呼吸信号一直是挑战性的，因为角度效应与场景中由呼吸引起的变化重叠。在运动建模的背景下，它们的主要缺点是这些方法中的大多数只提取一维信号，最多可以分解为幅度和相位。在本文中，我们使用Radon算子的线性来提出基于先前4D扫描的双线性模型以分离角度和呼吸变化。通过使用关于轨迹角度的先验知识的B样条插值来增强样本外扩展，以独立于获取角度来提取呼吸特征权重。虽然先前的四维扫描的先决条件似乎陡峭，但我们提出的呼吸运动估计在放射治疗中的应用通常满足这一要求。我们测试了我们对患者4D CT的DRR采取一次性留置法的方法，并在先前未见的视角的灰度值中实现了5.2％的平均估计误差。

##### URL
[https://arxiv.org/abs/1804.11227](https://arxiv.org/abs/1804.11227)

##### PDF
[https://arxiv.org/pdf/1804.11227](https://arxiv.org/pdf/1804.11227)

