---
layout: post
title: "Real-Time Patient-Specific Lung Radiotherapy Targeting using Deep Learning"
date: 2018-07-22 23:45:34
categories: arXiv_CV
tags: arXiv_CV Tracking CNN Deep_Learning
author: Markus D. Foote (1), Blake Zimmerman (1), Amit Sawant (2), Sarang Joshi (1) ((1) Scientific Computing and Imaging Institute, Department of Bioengineering, University of Utah, (2) Department of Radiation Oncology, The University of Maryland School of Medicine)
mathjax: true
---

* content
{:toc}

##### Abstract
Radiation therapy has presented a need for dynamic tracking of a target tumor volume. Fiducial markers such as implanted gold seeds have been used to gate radiation delivery but the markers are invasive and gating significantly increases treatment time. Pretreatment acquisition of a 4DCT allows for the development of accurate motion estimation for treatment planning. A deep convolutional neural network and subspace motion tracking is used to recover anatomical positions from a single radiograph projection in real-time. We approximate the nonlinear inverse of a diffeomorphic transformation composed with radiographic projection as a deep network that produces subspace coordinates to define the patient-specific deformation of the lungs from a baseline anatomic position. The geometric accuracy of the subspace projections on real patient data is similar to accuracy attained by original image registration between individual respiratory-phase image volumes.

##### Abstract (translated by Google)
放射疗法已经需要动态跟踪目标肿瘤体积。已经使用诸如植入的金种子之类的基准标记来控制辐射传递，但是标记是侵入性的并且门控显着增加了治疗时间。 4DCT的预处理获取允许开发用于治疗计划的准确运动估计。深度卷积神经网络和子空间运动跟踪用于实时地从单个射线照片投影中恢复解剖位置。我们将由射线照相投影组成的微分形变换的非线性逆近似为深度网络，该网络产生子空间坐标以从基线解剖位置定义肺部的患者特异性变形。实际患者数据上的子空间投影的几何精度类似于通过各个呼吸相位图像体积之间的原始图像配准所获得的精度。

##### URL
[http://arxiv.org/abs/1807.08388](http://arxiv.org/abs/1807.08388)

##### PDF
[http://arxiv.org/pdf/1807.08388](http://arxiv.org/pdf/1807.08388)

