---
layout: post
title: "PVR: Patch-to-Volume Reconstruction for Large Area Motion Correction of Fetal MRI"
date: 2016-11-25 17:54:39
categories: arXiv_CV
tags: arXiv_CV Super_Resolution GAN Optimization Quantitative Relation
author: Amir Alansary, Bernhard Kainz, Martin Rajchl, Maria Murgasova, Mellisa Damodaram, David F.A. Lloyd, Alice Davidson, Steven G. McDonagh, Mary Rutherford, Joseph V. Hajnal, Daniel Rueckert
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we present a novel method for the correction of motion artifacts that are present in fetal Magnetic Resonance Imaging (MRI) scans of the whole uterus. Contrary to current slice-to-volume registration (SVR) methods, requiring an inflexible anatomical enclosure of a single investigated organ, the proposed patch-to-volume reconstruction (PVR) approach is able to reconstruct a large field of view of non-rigidly deforming structures. It relaxes rigid motion assumptions by introducing a specific amount of redundant information that is exploited with parallelized patch-wise optimization, super-resolution, and automatic outlier rejection. We further describe and provide an efficient parallel implementation of PVR allowing its execution within reasonable time on commercially available graphics processing units (GPU), enabling its use in the clinical practice. We evaluate PVR's computational overhead compared to standard methods and observe improved reconstruction accuracy in presence of affine motion artifacts of approximately 30% compared to conventional SVR in synthetic experiments. Furthermore, we have evaluated our method qualitatively and quantitatively on real fetal MRI data subject to maternal breathing and sudden fetal movements. We evaluate peak-signal-to-noise ratio (PSNR), structural similarity index (SSIM), and cross correlation (CC) with respect to the originally acquired data and provide a method for visual inspection of reconstruction uncertainty. With these experiments we demonstrate successful application of PVR motion compensation to the whole uterus, the human fetus, and the human placenta.

##### Abstract (translated by Google)
在本文中，我们提出了一种新的方法来纠正在整个子宫的胎儿磁共振成像（MRI）扫描中出现的运动伪影。与目前的切片 - 体积配准（SVR）方法相反，要求对单个被调查的器官进行不灵活的解剖学包围，所提出的贴片 - 体积重建（PVR）方法能够重建非严格的大视场变形结构。它通过引入特定数量的冗余信息来缓解刚性运动假设，这些冗余信息是利用并行化的补丁式优化，超分辨率和自动异常排除来利用的。我们进一步描述并提供PVR的高效并行实现，允许其在合理的时间内在商业上可用的图形处理单元（GPU）上执行，使其能够在临床实践中使用。与标准方法相比，我们评估了PVR的计算开销，并且在合成实验中与常规SVR相比，仿射运动伪影存在约30％的情况下观察到改进的重构精度。此外，我们已经评估了我们的方法定性和定量的实际胎儿MRI数据受母体呼吸和突然胎动。我们评估了最初获取的数据的峰值信噪比（PSNR），结构相似性指数（SSIM）和互相关（CC），并提供了重建不确定度的目视检查方法。通过这些实验，我们证明PVR运动补偿在整个子宫，人胎儿和人胎盘上的成功应用。

##### URL
[https://arxiv.org/abs/1611.07289](https://arxiv.org/abs/1611.07289)

##### PDF
[https://arxiv.org/pdf/1611.07289](https://arxiv.org/pdf/1611.07289)

