---
layout: post
title: "Accurate Weakly Supervised Deep Lesion Segmentation on CT Scans: Self-Paced 3D Mask Generation from RECIST"
date: 2018-01-25 22:05:19
categories: arXiv_CV
tags: arXiv_CV Adversarial Super_Resolution Segmentation Weakly_Supervised CNN
author: Jinzheng Cai, Youbao Tang, Le Lu, Adam P. Harrison, Ke Yan, Jing Xiao, Lin Yang, Ronald M. Summers
mathjax: true
---

* content
{:toc}

##### Abstract
Volumetric lesion segmentation via medical imaging is a powerful means to precisely assess multiple time-point lesion/tumor changes. Because manual 3D segmentation is prohibitively time consuming and requires radiological experience, current practices rely on an imprecise surrogate called response evaluation criteria in solid tumors (RECIST). Despite their coarseness, RECIST marks are commonly found in current hospital picture and archiving systems (PACS), meaning they can provide a potentially powerful, yet extraordinarily challenging, source of weak supervision for full 3D segmentation. Toward this end, we introduce a convolutional neural network based weakly supervised self-paced segmentation (WSSS) method to 1) generate the initial lesion segmentation on the axial RECIST-slice; 2) learn the data distribution on RECIST-slices; 3) adapt to segment the whole volume slice by slice to finally obtain a volumetric segmentation. In addition, we explore how super-resolution images (2~5 times beyond the physical CT imaging), generated from a proposed stacked generative adversarial network, can aid the WSSS performance. We employ the DeepLesion dataset, a comprehensive CT-image lesion dataset of 32,735 PACS-bookmarked findings, which include lesions, tumors, and lymph nodes of varying sizes, categories, body regions and surrounding contexts. These are drawn from 10,594 studies of 4,459 patients. We also validate on a lymph-node dataset, where 3D ground truth masks are available for all images. For the DeepLesion dataset, we report mean Dice coefficients of 93% on RECIST-slices and 76% in 3D lesion volumes. We further validate using a subjective user study, where an experienced radiologist accepted our WSSS-generated lesion segmentation results with a high probability of 92.4%.

##### Abstract (translated by Google)
通过医学成像进行体积病变分割是精确评估多时间点病灶/肿瘤变化的有力手段。由于手动3D分割耗时过长且需要放射学经验，因此目前的实践依赖于在实体瘤中不准确的称为反应评估标准的替代标准（RECIST）。尽管其粗糙，RECIST标记在当前的医院图像和存档系统（PACS）中是常见的，这意味着它们可以为全3D分割提供潜在的强大但非常具有挑战性的弱监督源。为此，我们引入了一种基于卷积神经网络的弱监督自适应分割（WSSS）方法：1）生成轴向RECIST切片的初始病灶分割; 2）学习RECIST切片上的数据分布; 3）适应分片整片，最后得到一个体积分割。此外，我们探讨了如何从一个提出的堆叠生成敌对网络产生的超分辨率图像（超过物理CT成像的2〜5倍），可以帮助WSSS的性能。我们采用DeepLesion数据集，这是一个全面的CT图像病灶数据库，共有32,735个PACS书签，包括各种大小，类别，身体区域和周围环境的病变，肿瘤和淋巴结。这些来自对4,459名患者的10,594项研究。我们还在淋巴结数据集上进行验证，其中3D地面真值掩模可用于所有图像。对于DeepLesion数据集，我们报告RECIST切片的平均Dice系数为93％，3D病变体积为76％。我们进一步验证使用主观的用户研究，一个有经验的放射科医师接受我们的WSSS生成的病灶分割结果的概率高达92.4％。

##### URL
[http://arxiv.org/abs/1801.08614](http://arxiv.org/abs/1801.08614)

##### PDF
[http://arxiv.org/pdf/1801.08614](http://arxiv.org/pdf/1801.08614)

