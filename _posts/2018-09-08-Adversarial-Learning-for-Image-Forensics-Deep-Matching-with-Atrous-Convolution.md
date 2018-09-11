---
layout: post
title: "Adversarial Learning for Image Forensics Deep Matching with Atrous Convolution"
date: 2018-09-08 11:59:36
categories: arXiv_CV
tags: arXiv_CV Adversarial Detection Relation
author: Yaqi Liu, Xianfeng Zhao, Xiaobin Zhu, Yun Cao
mathjax: true
---

* content
{:toc}

##### Abstract
Constrained image splicing detection and localization (CISDL) is a newly proposed challenging task for image forensics, which investigates two input suspected images and identifies whether one image has suspected regions pasted from the other. In this paper, we propose a novel adversarial learning framework to train the deep matching network for CISDL. Our framework mainly consists of three building blocks: 1) the deep matching network based on atrous convolution (DMAC) aims to generate two high-quality candidate masks which indicate the suspected regions of the two input images, 2) the detection network is designed to rectify inconsistencies between the two corresponding candidate masks, 3) the discriminative network drives the DMAC network to produce masks that are hard to distinguish from ground-truth ones. In DMAC, atrous convolution is adopted to extract features with rich spatial information, the correlation layer based on the skip architecture is proposed to capture hierarchical features, and atrous spatial pyramid pooling is constructed to localize tampered regions at multiple scales. The detection network and the discriminative network act as the losses with auxiliary parameters to supervise the training of DMAC in an adversarial way. Extensive experiments, conducted on 21 generated testing sets and two public datasets, demonstrate the effectiveness of the proposed framework and the superior performance of DMAC.

##### Abstract (translated by Google)
约束图像拼接检测和定位（CISDL）是用于图像取证的新提出的挑战性任务，其调查两个输入的可疑图像并识别一个图像是否具有从另一个图像粘贴的可疑区域。在本文中，我们提出了一种新的对抗性学习框架来训练CISDL的深度匹配网络。我们的框架主要由三个构建块组成：1）基于迂回卷积（DMAC）的深度匹配网络旨在生成两个高质量候选掩码，指示两个输入图像的可疑区域，2）检测网络设计为纠正两个相应候选掩模之间的不一致性，3）辨别网络驱动DMAC网络以产生难以与地面真实区分的掩模。在DMAC中，采用atrous卷积提取具有丰富空间信息的特征，提出了基于跳过架构的相关层来捕获层次特征，并构造了不完全空间金字塔池，以定位多个尺度的篡改区域。检测网络和判别网络作为具有辅助参数的损失，以对抗方式监督DMAC的训练。在21个生成的测试集和两个公共数据集上进行的大量实验证明了所提出的框架的有效性和DMAC的优越性能。

##### URL
[http://arxiv.org/abs/1809.02791](http://arxiv.org/abs/1809.02791)

##### PDF
[http://arxiv.org/pdf/1809.02791](http://arxiv.org/pdf/1809.02791)

