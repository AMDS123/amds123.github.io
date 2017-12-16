---
layout: post
title: "Augmented Reality for Depth Cues in Monocular Minimally Invasive Surgery"
date: 2017-03-01 18:01:52
categories: arXiv_CV
tags: arXiv_CV Salient Sparse GAN Face Tracking Quantitative SLAM
author: Long Chen, Wen Tang, Nigel W. John, Tao Ruan Wan, Jian Jun Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
One of the major challenges in Minimally Invasive Surgery (MIS) such as laparoscopy is the lack of depth perception. In recent years, laparoscopic scene tracking and surface reconstruction has been a focus of investigation to provide rich additional information to aid the surgical process and compensate for the depth perception issue. However, robust 3D surface reconstruction and augmented reality with depth perception on the reconstructed scene are yet to be reported. This paper presents our work in this area. First, we adopt a state-of-the-art visual simultaneous localization and mapping (SLAM) framework - ORB-SLAM - and extend the algorithm for use in MIS scenes for reliable endoscopic camera tracking and salient point mapping. We then develop a robust global 3D surface reconstruction frame- work based on the sparse point clouds extracted from the SLAM framework. Our approach is to combine an outlier removal filter within a Moving Least Squares smoothing algorithm and then employ Poisson surface reconstruction to obtain smooth surfaces from the unstructured sparse point cloud. Our proposed method has been quantitatively evaluated compared with ground-truth camera trajectories and the organ model surface we used to render the synthetic simulation videos. In vivo laparoscopic videos used in the tests have demonstrated the robustness and accuracy of our proposed framework on both camera tracking and surface reconstruction, illustrating the potential of our algorithm for depth augmentation and depth-corrected augmented reality in MIS with monocular endoscopes.

##### Abstract (translated by Google)
微创手术（MIS）如腹腔镜手术的主要挑战之一是缺乏深度知觉。近年来，腹腔镜现场跟踪和表面重建一直是调查的重点，提供丰富的附加信息，以帮助手术过程和补偿深度知觉问题。然而，在重建的场景中具有深度感知的强健的三维表面重建和增强现实尚未被报道。本文介绍了我们在这方面的工作。首先，我们采用先进的视觉同时定位和映射（SLAM）框架 -  ORB-SLAM，并将用于MIS场景的算法扩展到可靠的内窥镜摄像机跟踪和显着点映射。然后，我们基于从SLAM框架中提取的稀疏点云，开发一个强大的全局三维表面重建框架。我们的方法是在移动最小二乘平滑算法中结合异常值去除滤波器，然后采用泊松曲面重构来从非结构化稀疏点云中获得光滑曲面。我们提出的方法已被定量评估与地面实况相机轨迹和我们用于渲染合成模拟视频的器官模型表面相比。在实验中使用的体内腹腔镜视频已经证明了我们提出的相机跟踪和表面重建框架的鲁棒性和准确性，说明了我们的算法用于单眼内窥镜MIS中的深度增强和深度校正的增强现实的潜力。

##### URL
[https://arxiv.org/abs/1703.01243](https://arxiv.org/abs/1703.01243)

##### PDF
[https://arxiv.org/pdf/1703.01243](https://arxiv.org/pdf/1703.01243)

