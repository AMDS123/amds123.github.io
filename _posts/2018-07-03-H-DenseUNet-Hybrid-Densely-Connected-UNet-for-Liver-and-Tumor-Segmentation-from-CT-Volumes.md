---
layout: post
title: "H-DenseUNet: Hybrid Densely Connected UNet for Liver and Tumor Segmentation from CT Volumes"
date: 2018-07-03 13:00:48
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Xiaomeng Li, Hao Chen, Xiaojuan Qi, Qi Dou, Chi-Wing Fu, Pheng Ann Heng
mathjax: true
---

* content
{:toc}

##### Abstract
Liver cancer is one of the leading causes of cancer death. To assist doctors in hepatocellular carcinoma diagnosis and treatment planning, an accurate and automatic liver and tumor segmentation method is highly demanded in the clinical practice. Recently, fully convolutional neural networks (FCNs), including 2D and 3D FCNs, serve as the back-bone in many volumetric image segmentation. However, 2D convolutions can not fully leverage the spatial information along the third dimension while 3D convolutions suffer from high computational cost and GPU memory consumption. To address these issues, we propose a novel hybrid densely connected UNet (H-DenseUNet), which consists of a 2D DenseUNet for efficiently extracting intra-slice features and a 3D counterpart for hierarchically aggregating volumetric contexts under the spirit of the auto-context algorithm for liver and tumor segmentation. We formulate the learning process of H-DenseUNet in an end-to-end manner, where the intra-slice representations and inter-slice features can be jointly optimized through a hybrid feature fusion (HFF) layer. We extensively evaluated our method on the dataset of MICCAI 2017 Liver Tumor Segmentation (LiTS) Challenge and 3DIRCADb Dataset. Our method outperformed other state-of-the-arts on the segmentation results of tumors and achieved very competitive performance for liver segmentation even with a single model.

##### Abstract (translated by Google)
肝癌是导致癌症死亡的主要原因之一。为了帮助医生进行肝细胞癌的诊断和治疗计划，在临床实践中高度需要准确和自动的肝脏和肿瘤分割方法。最近，完全卷积神经网络（FCN），包括2D和3D FCN，在许多体积图像分割中充当了骨干。然而，2D卷积不能充分利用沿第三维的空间信息，而3D卷绕遭受高计算成本和GPU内存消耗。为了解决这些问题，我们提出了一种新颖的混合密集连接的UNet（H-DenseUNet），它包括用于有效提取片内特征的2D DenseUNet和用于在自动上下文算法的精神下分层聚合体积上下文的3D对应物。用于肝脏和肿瘤分割。我们以端到端的方式制定H-DenseUNet的学习过程，其中可以通过混合特征融合（HFF）层联合优化片内表示和片间特征。我们在MICCAI 2017肝肿瘤分割（LiTS）挑战和3DIRCADb数据集的数据集上广泛评估了我们的方法。我们的方法在肿瘤分割结果方面优于其他现有技术，并且即使使用单一模型也能实现肝脏分割的非常有竞争力的表现。

##### URL
[http://arxiv.org/abs/1709.07330](http://arxiv.org/abs/1709.07330)

##### PDF
[http://arxiv.org/pdf/1709.07330](http://arxiv.org/pdf/1709.07330)

