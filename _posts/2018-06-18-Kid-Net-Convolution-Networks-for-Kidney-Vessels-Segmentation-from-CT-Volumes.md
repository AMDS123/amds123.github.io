---
layout: post
title: "Kid-Net: Convolution Networks for Kidney Vessels Segmentation from CT-Volumes"
date: 2018-06-18 15:25:07
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Classification Quantitative
author: Ahmed Taha, Pechin Lo, Junning Li, Tao Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic image segmentation plays an important role in modeling patient-specific anatomy. We propose a convolution neural network, called Kid-Net, along with a training schema to segment kidney vessels: artery, vein and collecting system. Such segmentation is vital during the surgical planning phase in which medical decisions are made before surgical incision. Our main contribution is developing a training schema that handles unbalanced data, reduces false positives and enables high-resolution segmentation with a limited memory budget. These objectives are attained using dynamic weighting, random sampling and 3D patch segmentation. Manual medical image annotation is both time-consuming and expensive. Kid-Net reduces kidney vessels segmentation time from matter of hours to minutes. It is trained end-to-end using 3D patches from volumetric CT-images. A complete segmentation for a 512x512x512 CT-volume is obtained within a few minutes (1-2 mins) by stitching the output 3D patches together. Feature down-sampling and up-sampling are utilized to achieve higher classification and localization accuracies. Quantitative and qualitative evaluation results on a challenging testing dataset show Kid-Net competence.

##### Abstract (translated by Google)
语义图像分割在模拟患者特定解剖结构中起着重要作用。我们提出了一个名为Kid-Net的卷积神经网络，以及一个训练模式来分割肾血管：动脉，静脉和收集系统。这种分割在外科手术切割前做出医疗决定的手术计划阶段是至关重要的。我们的主要贡献是开发一种处理不平衡数据的训练模式，减少误报并以有限的内存预算实现高分辨率分割。这些目标是通过使用动态加权，随机采样和3D补丁分割来实现的。手动医疗图像注释既费时又昂贵。 Kid-Net可将肾血管分割时间从几小时缩短到几分钟。它使用体积CT图像中的3D贴片进行端对端训练。通过将输出3D贴片拼接在一起，可以在几分钟（1-2分钟）内完成对512x512x512 CT体积的完整分割。采用特征下采样和上采样来实现更高的分类和定位精度。在具有挑战性的测试数据集上的定量和定性评估结果显示Kid-Net能力。

##### URL
[http://arxiv.org/abs/1806.06769](http://arxiv.org/abs/1806.06769)

##### PDF
[http://arxiv.org/pdf/1806.06769](http://arxiv.org/pdf/1806.06769)

