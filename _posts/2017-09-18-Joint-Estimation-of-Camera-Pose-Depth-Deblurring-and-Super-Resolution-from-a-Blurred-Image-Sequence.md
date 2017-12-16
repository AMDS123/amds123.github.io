---
layout: post
title: "Joint Estimation of Camera Pose, Depth, Deblurring, and Super-Resolution from a Blurred Image Sequence"
date: 2017-09-18 02:24:31
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Pose_Estimation Optimization
author: Haesol Park, Kyoung Mu Lee
mathjax: true
---

* content
{:toc}

##### Abstract
The conventional methods for estimating camera poses and scene structures from severely blurry or low resolution images often result in failure. The off-the-shelf deblurring or super-resolution methods may show visually pleasing results. However, applying each technique independently before matching is generally unprofitable because this naive series of procedures ignores the consistency between images. In this paper, we propose a pioneering unified framework that solves four problems simultaneously, namely, dense depth reconstruction, camera pose estimation, super-resolution, and deblurring. By reflecting a physical imaging process, we formulate a cost minimization problem and solve it using an alternating optimization technique. The experimental results on both synthetic and real videos show high-quality depth maps derived from severely degraded images that contrast the failures of naive multi-view stereo methods. Our proposed method also produces outstanding deblurred and super-resolved images unlike the independent application or combination of conventional video deblurring, super-resolution methods.

##### Abstract (translated by Google)
用于从严重模糊或低分辨率图像估计相机姿态和场景结构的传统方法经常导致失败。现成的去模糊或超分辨率方法可能显示出令人满意的结果。然而，在匹配之前独立应用每种技术通常是无利可图的，因为这一系列简单的过程忽略了图像之间的一致性。在本文中，我们提出了一个开创性的统一框架，同时解决四个问题，即密集深度重建，相机姿态估计，超分辨率和去模糊。通过反映物理成像过程，我们制定了成本最小化问题，并使用交替优化技术来解决它。合成视频和真实视频的实验结果显示，从严重退化的图像获得的高质量深度图对比了朴素多视图立体方法的失败。我们提出的方法也产生出色的去模糊和超分辨图像，不像独立应用或传统视频去模糊，超分辨方法的组合。

##### URL
[https://arxiv.org/abs/1709.05745](https://arxiv.org/abs/1709.05745)

##### PDF
[https://arxiv.org/pdf/1709.05745](https://arxiv.org/pdf/1709.05745)

