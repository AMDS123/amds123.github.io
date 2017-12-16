---
layout: post
title: "Mesh-to-raster based non-rigid registration of multi-modal images"
date: 2017-10-31 15:35:05
categories: arXiv_CV
tags: arXiv_CV Segmentation Face Quantitative
author: Rosalia Tatano, Benjamin Berkels, Thomas M. Deserno
mathjax: true
---

* content
{:toc}

##### Abstract
Region of interest (ROI) alignment in medical images plays a crucial role in diagnostics, procedure planning, treatment, and follow-up. Frequently, a model is represented as triangulated mesh while the patient data is provided from CAT scanners as pixel or voxel data. Previously, we presented a 2D method for curve-to-pixel registration. This paper contributes (i) a general mesh-to-raster (M2R) framework to register ROIs in multi-modal images; (ii) a 3D surface-to-voxel application, and (iii) a comprehensive quantitative evaluation in 2D using ground truth provided by the simultaneous truth and performance level estimation (STAPLE) method. The registration is formulated as a minimization problem where the objective consists of a data term, which involves the signed distance function of the ROI from the reference image, and a higher order elastic regularizer for the deformation. The evaluation is based on quantitative light-induced fluoroscopy (QLF) and digital photography (DP) of decalcified teeth. STAPLE is computed on 150 image pairs from 32 subjects, each showing one corresponding tooth in both modalities. The ROI in each image is manually marked by three experts (900 curves in total). In the QLF-DP setting, our approach significantly outperforms the mutual information-based registration algorithm implemented with the Insight Segmentation and Registration Toolkit (ITK) and Elastix.

##### Abstract (translated by Google)
医学图像中的感兴趣区域（ROI）调整在诊断，程序规划，治疗和随访中起着至关重要的作用。通常，模型被表示为三角网格，而患者数据是从CAT扫描仪提供的像素或体素数据。以前，我们提出了一个曲线到像素配准的2D方法。本文提供（i）一个通用的网格到栅格（M2R）框架来注册多模态图像的投资回报率; （ii）3D表面到体素应用，以及（iii）使用由同时真实和性能水平估计（STAPLE）方法提供的基本事实进行2D中的全面定量评估。这种配准是一个最小化问题，其中的目标由一个数据项组成，这个数据项涉及参考图像的ROI的有符号距离函数，以及一个用于变形的高阶弹性正则化器。评估是基于定量光诱导荧光透视（QLF）和数字摄影（DP）的脱钙牙齿。 STAPLE计算来自32个科目的150个图像对，每个显示两个模态中的一个对应的牙齿。每个图像的ROI由三名专家（总共900条曲线）手动标记。在QLF-DP设置中，我们的方法明显优于Insight分段和注册工具包（ITK）和Elastix实施的基于互信息的注册算法。

##### URL
[https://arxiv.org/abs/1703.01972](https://arxiv.org/abs/1703.01972)

##### PDF
[https://arxiv.org/pdf/1703.01972](https://arxiv.org/pdf/1703.01972)

