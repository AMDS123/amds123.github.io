---
layout: post
title: "The method of multimodal MRI brain image segmentation based on differential geometric features"
date: 2018-11-10 16:46:28
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Yongpei Zhu, Zicong Zhou, Guojun Liao, Qianxi Yang, Kehong Yuan
mathjax: true
---

* content
{:toc}

##### Abstract
Accurate segmentation of brain tissue in magnetic resonance images (MRI) is a diffcult task due to different types of brain abnormalities. Using information and features from multimodal MRI including T1, T1-weighted inversion recovery (T1-IR) and T2-FLAIR and differential geometric features including the Jacobian determinant(JD) and the curl vector(CV) derived from T1 modality can result in a more accurate analysis of brain images. In this paper, we use the differential geometric information including JD and CV as image characteristics to measure the differences between different MRI images, which represent local size changes and local rotations of the brain image, and we can use them as one CNN channel with other three modalities (T1-weighted, T1-IR and T2-FLAIR) to get more accurate results of brain segmentation. We test this method on two datasets including IBSR dataset and MRBrainS datasets based on the deep voxelwise residual network, namely VoxResNet, and obtain excellent improvement over single modality or three modalities and increases average DSC(Cerebrospinal Fluid (CSF), Gray Matter (GM) and White Matter (WM)) by about 1.5% on the well-known MRBrainS18 dataset and about 2.5% on the IBSR dataset. Moreover, we discuss that one modality combined with its JD or CV information can replace the segmentation effect of three modalities, which can provide medical conveniences for doctor to diagnose because only to extract T1-modality MRI image of patients. Finally, we also compare the segmentation performance of our method in two networks, VoxResNet and U-Net network. The results show VoxResNet has a better performance than U-Net network with our method in brain MRI segmentation. We believe the proposed method can advance the performance in brain segmentation and clinical diagnosis.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.04281](http://arxiv.org/abs/1811.04281)

##### PDF
[http://arxiv.org/pdf/1811.04281](http://arxiv.org/pdf/1811.04281)

