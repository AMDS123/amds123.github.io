---
layout: post
title: "Simultaneous Multiple Surface Segmentation Using Deep Learning"
date: 2017-05-19 18:43:07
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN Face CNN Optimization Deep_Learning Quantitative
author: Abhay Shah, Michael Abramoff, Xiaodong Wu
mathjax: true
---

* content
{:toc}

##### Abstract
The task of automatically segmenting 3-D surfaces representing boundaries of objects is important for quantitative analysis of volumetric images, and plays a vital role in biomedical image analysis. Recently, graph-based methods with a global optimization property have been developed and optimized for various medical imaging applications. Despite their widespread use, these require human experts to design transformations, image features, surface smoothness priors, and re-design for a different tissue, organ or imaging modality. Here, we propose a Deep Learning based approach for segmentation of the surfaces in volumetric medical images, by learning the essential features and transformations from training data, without any human expert intervention. We employ a regional approach to learn the local surface profiles. The proposed approach was evaluated on simultaneous intraretinal layer segmentation of optical coherence tomography (OCT) images of normal retinas and retinas affected by age related macular degeneration (AMD). The proposed approach was validated on 40 retina OCT volumes including 20 normal and 20 AMD subjects. The experiments showed statistically significant improvement in accuracy for our approach compared to state-of-the-art graph based optimal surface segmentation with convex priors (G-OSC). A single Convolution Neural Network (CNN) was used to learn the surfaces for both normal and diseased images. The mean unsigned surface positioning errors obtained by G-OSC method 2.31 voxels (95% CI 2.02-2.60 voxels) was improved to $1.27$ voxels (95% CI 1.14-1.40 voxels) using our new approach. On average, our approach takes 94.34 s, requiring 95.35 MB memory, which is much faster than the 2837.46 s and 6.87 GB memory required by the G-OSC method on the same computer system.

##### Abstract (translated by Google)
自动分割表示物体边界的三维表面的任务对于体积图像的定量分析是重要的，并且在生物医学图像分析中起着至关重要的作用。最近，针对各种医学成像应用开发并优化了具有全局优化性质的基于图的方法。尽管它们被广泛使用，但这需要人类专家来设计转换，图像特征，表面平滑度的先验以及针对不同组织，器官或成像模式的重新设计。在这里，我们提出了一种基于深度学习的方法来分割体积医学图像中的表面，通过学习训练数据的基本特征和转换，而不需要任何人类专家的干预。我们采用区域方法来学习当地的表面轮廓。提出的方法进行了评估同时intraretinal层分割光学相干断层扫描（OCT）图像的正常视网膜和视网膜受年龄相关性黄斑变性（AMD）的影响。所提出的方法在40个视网膜OCT体积上进行了验证，包括20个正常和20个AMD受试者。与基于最先进的基于凸面先验（G-OSC）的最佳表面分割相比，实验显示了我们的方法在统计学上显着的准确性提高。使用单个卷积神经网络（CNN）来学习正常和患病图像的表面。使用我们的新方法，通过G-OSC方法2.31体素（95％CI 2.02-2.60体素）获得的平均无符号表面定位误差被改进为1.27美元体素（95％CI 1.14-1.40体素）。平均而言，我们的方法需要94.34 s，需要95.35 MB的内存，比同一计算机系统上的G-OSC方法所需的2837.46 s和6.87 GB的内存要快得多。

##### URL
[https://arxiv.org/abs/1705.07142](https://arxiv.org/abs/1705.07142)

##### PDF
[https://arxiv.org/pdf/1705.07142](https://arxiv.org/pdf/1705.07142)

