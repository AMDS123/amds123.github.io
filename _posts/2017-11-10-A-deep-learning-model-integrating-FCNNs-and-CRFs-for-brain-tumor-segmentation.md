---
layout: post
title: "A deep learning model integrating FCNNs and CRFs for brain tumor segmentation"
date: 2017-11-10 02:49:49
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN RNN Deep_Learning
author: Xiaomei Zhao, Yihong Wu, Guidong Song, Zhenye Li, Yazhuo Zhang, Yong Fan
mathjax: true
---

* content
{:toc}

##### Abstract
Accurate and reliable brain tumor segmentation is a critical component in cancer diagnosis, treatment planning, and treatment outcome evaluation. Build upon successful deep learning techniques, a novel brain tumor segmentation method is developed by integrating fully convolutional neural networks (FCNNs) and Conditional Random Fields (CRFs) in a unified framework to obtain segmentation results with appearance and spatial consistency. We train a deep learning based segmentation model using 2D image patches and image slices in following steps: 1) training FCNNs using image patches; 2) training CRFs as Recurrent Neural Networks (CRF-RNN) using image slices with parameters of FCNNs fixed; and 3) fine-tuning the FCNNs and the CRF-RNN using image slices. Particularly, we train 3 segmentation models using 2D image patches and slices obtained in axial, coronal and sagittal views respectively, and combine them to segment brain tumors using a voting based fusion strategy. Our method could segment brain images slice-by-slice, much faster than those based on image patches. We have evaluated our method based on imaging data provided by the Multimodal Brain Tumor Image Segmentation Challenge (BRATS) 2013, BRATS 2015 and BRATS 2016. The experimental results have demonstrated that our method could build a segmentation model with Flair, T1c, and T2 scans and achieve competitive performance as those built with Flair, T1, T1c, and T2 scans.

##### Abstract (translated by Google)
准确可靠的脑肿瘤分割是癌症诊断，治疗计划和治疗结果评估的关键组成部分。在成功的深度学习技术的基础上，将完全卷积神经网络（FCNNs）和条件随机场（CRFs）集成在一个统一的框架下，开发了一种新颖的脑肿瘤分割方法，获得了具有外观和空间一致性的分割结果。我们训练基于深度学习的分割模型使用二维图像补丁和图像切片在以下步骤：1）使用图像补丁训练FCNNs; 2）使用具有固定的FCNN参数的图像切片对CRF作为递归神经网络（CRF-RNN）进行训练;和3）使用图像切片来微调FCNN和CRF-RNN。特别地，我们使用分别在轴向，冠状面和矢状面上获得的2D图像块和切片来训练3个分割模型，并且使用基于投票的融合策略将它们组合以分割脑肿瘤。我们的方法可以逐片地分割大脑图像，比基于图像补丁的快得多。我们根据多模脑肿瘤图像分割挑战（BRATS）2013，BRATS 2015和BRATS 2016提供的成像数据评估了我们的方法。实验结果表明，我们的方法可以建立Flair，T1c和T2扫描的分割模型并通过Flair，T1，T1c和T2扫描获得具有竞争力的性能。

##### URL
[https://arxiv.org/abs/1702.04528](https://arxiv.org/abs/1702.04528)

##### PDF
[https://arxiv.org/pdf/1702.04528](https://arxiv.org/pdf/1702.04528)

