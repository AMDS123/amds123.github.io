---
layout: post
title: "MRI-PET Registration with Automated Algorithm in Pre-clinical Studies"
date: 2017-05-23 13:42:39
categories: arXiv_CV
tags: arXiv_CV GAN Quantitative
author: Nathanael L. Baisa, Stéphanie Bricq, Alain Lalande
mathjax: true
---

* content
{:toc}

##### Abstract
Magnetic Resonance Imaging (MRI) and Positron Emission Tomography (PET) automatic 3-D registration is implemented and validated for small animal image volumes so that the high-resolution anatomical MRI information can be fused with the low spatial resolution of functional PET information for the localization of lesion that is currently in high demand in the study of tumor of cancer (oncology) and its corresponding preparation of pharmaceutical drugs. Though many registration algorithms are developed and applied on human brain volumes, these methods may not be as efficient on small animal datasets due to lack of intensity information and often the high anisotropy in voxel dimensions. Therefore, a fully automatic registration algorithm which can register not only assumably rigid small animal volumes such as brain but also deformable organs such as kidney, cardiac and chest is developed using a combination of global affine and local B-spline transformation models in which mutual information is used as a similarity criterion. The global affine registration uses a multi-resolution pyramid on image volumes of 3 levels whereas in local B-spline registration, a multi-resolution scheme is applied on the B-spline grid of 2 levels on the finest resolution of the image volumes in which only the transform itself is affected rather than the image volumes. Since mutual information lacks sufficient spatial information, PCA is used to inject it by estimating initial translation and rotation parameters. It is computationally efficient since it is implemented using C++ and ITK library, and is qualitatively and quantitatively shown that this PCA-initialized global registration followed by local registration is in close agreement with expert manual registration and outperforms the one without PCA initialization tested on small animal brain and kidney.

##### Abstract (translated by Google)
磁共振成像（MRI）和正电子发射断层扫描（PET）自动三维配准是实施和小动物图像卷验证，使高分辨率的解剖磁共振成像信息可融合功能的PET信息的低空间分辨率为目前在癌症肿瘤研究（肿瘤学）方面的高需求病变的定位及其相应的药物制剂。虽然许多配准算法被开发和应用在人脑容量上，但是由于缺少强度信息以及常常在体素维中具有高度的各向异性，所以这些方法在小动物数据集上可能效率不高。因此，使用全局仿射和局部B样条变换模型的组合来开发全自动配准算法，其不仅可以记录如脑的刚性小动物体积，而且还可以记录诸如肾，心脏和胸部的可变形器官，其中互信息被用作相似性标准。全局仿射配准在3个图像的图像体积上使用多分辨率金字塔，而在局部B样条配准中，将多分辨率方案应用于图像体积的最佳分辨率的2级B样条网格，其中只有变换本身受到影响，而不是影像的体积。由于互信息缺乏足够的空间信息，PCA被用来通过估计初始平移和旋转参数来注入。由于它是使用C ++和ITK库实现的，并且定性和定量地显示，这种PCA初始化的全局注册跟随着本地注册与专家手动注册非常吻合，并且在未经PCA初始化测试的小动物脑和肾。

##### URL
[https://arxiv.org/abs/1705.07062](https://arxiv.org/abs/1705.07062)

##### PDF
[https://arxiv.org/pdf/1705.07062](https://arxiv.org/pdf/1705.07062)

