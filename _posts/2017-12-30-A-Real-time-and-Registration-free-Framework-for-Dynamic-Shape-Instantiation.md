---
layout: post
title: "A Real-time and Registration-free Framework for Dynamic Shape Instantiation"
date: 2017-12-30 19:25:09
categories: arXiv_CV
tags: arXiv_CV Sparse GAN Relation
author: Xiao-Yun Zhou, Guang-Zhong Yang, Su-Lin Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Real-time 3D navigation during minimally invasive procedures is an essential yet challenging task, especially when considerable tissue motion is involved. To balance image acquisition speed and resolution, only 2D images or low-resolution 3D volumes can be used clinically. In this paper, a real-time and registration-free framework for dynamic shape instantiation, generalizable to multiple anatomical applications, is proposed to instantiate high-resolution 3D shapes of an organ from a single 2D image intra-operatively. Firstly, an approximate optimal scan plane was determined by analyzing the pre-operative 3D statistical shape model (SSM) of the anatomy with sparse principal component analysis (SPCA) and considering practical constraints . Secondly, kernel partial least squares regression (KPLSR) was used to learn the relationship between the pre-operative 3D SSM and a synchronized 2D SSM constructed from 2D images obtained at the approximate optimal scan plane. Finally, the derived relationship was applied to the new intra-operative 2D image obtained at the same scan plane to predict the high-resolution 3D shape intra-operatively. A major feature of the proposed framework is that no extra registration between the pre-operative 3D SSM and the synchronized 2D SSM is required. Detailed validation was performed on studies including the liver and right ventricle (RV) of the heart. The derived results (mean accuracy of 2.19mm on patients and computation speed of 1ms) demonstrate its potential clinical value for real-time, high-resolution, dynamic and 3D interventional guidance.

##### Abstract (translated by Google)
微创手术过程中的实时三维导航是一项重要且具有挑战性的任务，特别是在涉及大量组织运动的情况下。为了平衡图像采集速度和分辨率，临床上只能使用2D图像或低分辨率的3D图像。在本文中，提出了一种动态形状实例化的实时免注册框架，可以推广到多种解剖学应用，以便在手术中从单个2D图像实例化一个器官的高分辨率三维形状。首先，采用稀疏主成分分析（SPCA）分析术前三维统计形状模型（SSM），并考虑实际约束条件，确定近似最佳的扫描平面。其次，利用核偏最小二乘回归（KPLSR）学习术前三维SSM与由近似最优扫描平面获得的二维图像构建的同步二维SSM之间的关系。最后，将推导出的关系应用于在同一扫描平面上获得的新的术中2D图像，以便在手术中预测高分辨率3D形状。所提出的框架的主要特征是在术前3D SSM和同步2D SSM之间不需要额外的注册。对包括心脏的肝脏和右心室（RV）在内的研究进行了详细的验证。所得结果（患者的平均准确度为2.19mm，计算速度为1ms）对于实时，高分辨率，动态和三维介入指导具有潜在的临床应用价值。

##### URL
[http://arxiv.org/abs/1801.00182](http://arxiv.org/abs/1801.00182)

##### PDF
[http://arxiv.org/pdf/1801.00182](http://arxiv.org/pdf/1801.00182)

