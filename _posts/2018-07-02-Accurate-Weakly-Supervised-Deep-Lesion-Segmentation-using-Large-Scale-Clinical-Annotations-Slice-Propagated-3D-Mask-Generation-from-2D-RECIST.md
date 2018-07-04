---
layout: post
title: "Accurate Weakly-Supervised Deep Lesion Segmentation using Large-Scale Clinical Annotations: Slice-Propagated 3D Mask Generation from 2D RECIST"
date: 2018-07-02 00:17:42
categories: arXiv_CV
tags: arXiv_CV Segmentation Weakly_Supervised CNN
author: Jinzheng Cai, Youbao Tang, Le Lu, Adam P. Harrison, Ke Yan, Jing Xiao, Lin Yang, Ronald M. Summers
mathjax: true
---

* content
{:toc}

##### Abstract
Volumetric lesion segmentation from computed tomography (CT) images is a powerful means to precisely assess multiple time-point lesion/tumor changes. However, because manual 3D segmentation is prohibitively time consuming, current practices rely on an imprecise surrogate called response evaluation criteria in solid tumors (RECIST). Despite their coarseness, RECIST markers are commonly found in current hospital picture and archiving systems (PACS), meaning they can provide a potentially powerful, yet extraordinarily challenging, source of weak supervision for full 3D segmentation. Toward this end, we introduce a convolutional neural network (CNN) based weakly supervised slice-propagated segmentation (WSSS) method to 1) generate the initial lesion segmentation on the axial RECIST-slice; 2) learn the data distribution on RECIST-slices; 3) extrapolate to segment the whole lesion slice by slice to finally obtain a volumetric segmentation. To validate the proposed method, we first test its performance on a fully annotated lymph node dataset, where WSSS performs comparably to its fully supervised counterparts. We then test on a comprehensive lesion dataset with 32,735 RECIST marks, where we report a mean Dice score of 92% on RECIST-marked slices and 76% on the entire 3D volumes.

##### Abstract (translated by Google)
计算机断层扫描（CT）图像的体积病变分割是精确评估多个时间点病变/肿瘤变化的有力手段。然而，由于手动3D分割非常耗时，目前的实践依赖于实体瘤（RECIST）中称为响应评估标准的不精确替代物。尽管它们很粗糙，RECIST标记通常出现在当前的医院图片和归档系统（PACS）中，这意味着它们可以为完整的3D分割提供潜在的强大但极其具有挑战性的弱监督源。为此，我们引入了基于卷积神经网络（CNN）的弱监督切片传播分割（WSSS）方法，1）在轴向RECIST切片上生成初始病变分割; 2）学习RECIST-slice上的数据分布; 3）外推以逐片切割整个病变，最终获得体积分割。为了验证所提出的方法，我们首先在完全注释的淋巴结数据集上测试其性能，其中WSSS的表现与其完全受监督的对应物相当。然后，我们对具有32,735个RECIST标记的综合病变数据集进行测试，其中我们报告RECIST标记切片的平均Dice评分为92％，整个3D体积的平均Dice评分为76％。

##### URL
[https://arxiv.org/abs/1807.01172](https://arxiv.org/abs/1807.01172)

##### PDF
[https://arxiv.org/pdf/1807.01172](https://arxiv.org/pdf/1807.01172)

