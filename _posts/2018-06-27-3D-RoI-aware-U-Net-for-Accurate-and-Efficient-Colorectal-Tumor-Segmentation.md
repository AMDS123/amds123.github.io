---
layout: post
title: "3D RoI-aware U-Net for Accurate and Efficient Colorectal Tumor Segmentation"
date: 2018-06-27 08:42:58
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Yi-Jie Huang, Qi Dou, Zi-Xian Wang, Li-Zhi Liu, Ying Jin, Chao-Feng Li, Lisheng Wang, Hao Chen, Rui-Hua Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Objective: Segmentation of colorectal cancerous regions from the Magnetic Resonance (MR) image is a crucial procedure for radiotherapy, which requires to accurately delineate boundaries of the tumors. This work aims to address this important while challenging task in an accurate as well as efficient manner. Methods: We propose a novel multi-tasking framework, referred to as 3D RoI-aware U-Net (3D RU-Net), for RoI localization and intra-RoI segmentation, where the two tasks share one backbone network. With the region proposals from the localization branch, we crop multi-level feature maps from the backbone network to form a U-Net-like intra-RoI segmentation branch. To effectively train the model, we propose a novel Dice based hybrid loss to tackle the issue of class-imbalance under the multi-task setting. Furthermore, we design a multi-resolution model ensemble strategy to improve the discrimination capability of the framework. Results: Our method has been validated on 64 cancerous cases with a four-fold cross-validation, outperforming state-of-the-art methods by a significant margin in terms of both accuracy and speed. Conclusion: Experimental results demonstrated that the proposed method enables accurate and fast whole volume RoI localization and intra-RoI segmentation. Significance: This paper proposes a general 3D segmentation framework which rapidly locates the RoI region in large volumetric images and accurately segments the in-region targets. The method has a great potential to be extended to other small 3D object segmentation tasks from medical images.

##### Abstract (translated by Google)
目的：从磁共振（MR）图像中分割结直肠癌区域是放疗的关键步骤，其需要准确描绘肿瘤的边界。这项工作旨在以准确和高效的方式解决这一重要挑战。方法：我们提出了一种新的多任务框架，称为3D RoI-aware U-Net（3D RU-Net），用于RoI本地化和RoI内分割，其中两项任务共享一个骨干网络。通过本地化分支的区域提案，我们从骨干网络中裁剪出多层次的特征地图，形成一个类似于U-Net的内部RoI分割分支。为了有效地训练模型，我们提出了一种基于Dice的新型混合损失来解决多任务设置下的类失衡问题。此外，我们设计了一个多分辨率模型集成策略来提高框架的识别能力。结果：我们的方法已通过四次交叉验证在64例癌症病例中得到验证，在准确性和速度方面均优于现有技术方法。结论：实验结果表明，所提出的方法能够实现准确和快速的整卷RoI定位和RoI内分割。意义：本文提出了一种通用的3D分割框架，可以快速定位RoI区域的大体积图像，并精确分割区域内目标。该方法有很大的潜力可以扩展到医学图像中的其他小型3D对象分割任务。

##### URL
[http://arxiv.org/abs/1806.10342](http://arxiv.org/abs/1806.10342)

##### PDF
[http://arxiv.org/pdf/1806.10342](http://arxiv.org/pdf/1806.10342)

