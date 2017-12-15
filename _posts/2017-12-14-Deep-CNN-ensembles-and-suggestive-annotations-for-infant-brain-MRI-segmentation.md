---
layout: post
title: "Deep CNN ensembles and suggestive annotations for infant brain MRI segmentation"
date: 2017-12-14 16:27:42
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation CNN Quantitative
author: Jose Dolz, Christian Desrosiers, Li Wang, Jing Yuan, Dinggang Shen, Ismail Ben Ayed
mathjax: true
---

* content
{:toc}

##### Abstract
Precise 3D segmentation of infant brain tissues is an essential step towards comprehensive volumetric studies and quantitative analysis of early brain developement. However, computing such segmentations is very challenging, especially for the infant brain at round 6-month of age, due to the poor image quality, among other difficulties inherent to infant brain MRI, e.g., the isointense contrast between white and gray matter and the severe partial volume effect due to small brain sizes. This study investigates the problem with an ensemble of semi-dense fully convolutional neural networks (CNNs), which employs T1-weighted and T2-weighted MR images as input. We demonstrate that the ensemble agreement is highly correlated with the segmentation errors. Therefore, our method provides measures that can guide local user corrections. To the best of our knowledge, this work is the first ensemble of 3D CNNs for suggesting annotations within images. Furthermore, inspired by the very recent success of dense networks, we propose a novel architecture, SemiDenseNet, which connects all convolutional layers directly to the end of the network. Our architecture allows the efficient propagation of gradients during training, while limiting the number of parameters, requiring one order of magnitude less parameters than popular medical image segmentation networks such as 3D U-Net. Another contribution of our work is the study of the impact that early or late fusions of multiple image modalities might have on the performances of deep architectures. We report evaluations of our method on the public data of the MICCAI iSEG-2017 Challenge on 6-month infant brain MRI segmentation, and show very competitive results among 21 teams, ranking first or second in most metrics.

##### Abstract (translated by Google)
婴幼儿脑组织的精确三维分割是全脑容量研究和早期脑发育定量分析的必要步骤。然而，计算这种分割是非常具有挑战性的，特别是对于6个月大的婴儿的大脑，由于图像质量差以及婴儿大脑MRI所固有的其他困难，例如，白色和灰质之间的等强对比以及严重的部分体积效应，由于小脑的大小。本研究利用半稠密全卷积神经网络（CNN）的集合来研究该问题，其使用T1加权和T2加权MR图像作为输入。我们证明合奏协议与分割错误高度相关。因此，我们的方法提供了指导本地用户更正的措施。据我们所知，这项工作是第一个3D CNN合奏，用于在图像中提示注释。此外，受密集网络最近的成功启发，我们提出了一种新的架构，SemiDenseNet，它将所有的卷积层直接连接到网络的末端。我们的架构允许训练期间梯度的有效传播，同时限制参数的数量，比诸如3D U-Net的流行的医学图像分割网络要求的参数少一个数量级。我们的工作的另一个贡献是研究多种图像模式的早期融合或后期融合对深层架构性能的影响。我们对6个月婴儿脑MRI分割的MICCAI iSEG-2017挑战公开数据进行了评估，并在21个队伍中显示出非常有竞争力的结果，在大多数指标中排名第一或第二。

##### URL
[http://arxiv.org/abs/1712.05319](http://arxiv.org/abs/1712.05319)

##### PDF
[http://arxiv.org/pdf/1712.05319](http://arxiv.org/pdf/1712.05319)

