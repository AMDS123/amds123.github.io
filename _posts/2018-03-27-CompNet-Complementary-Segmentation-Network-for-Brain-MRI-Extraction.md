---
layout: post
title: "CompNet: Complementary Segmentation Network for Brain MRI Extraction"
date: 2018-03-27 03:26:22
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Raunak Dey, Yi Hong
mathjax: true
---

* content
{:toc}

##### Abstract
Brain extraction is a fundamental step for most brain imaging studies. In this paper, we investigate the problem of skull stripping and propose complementary segmentation networks (CompNets) to accurately extract the brain from T1-weighted MRI scans, for both normal and pathological brain images. The proposed networks are designed in the framework of encoder-decoder networks and have two pathways to learn features from both brain tissues and their complementary part located outside of the brain. The complementary pathway extracts the features in the non-brain region and leads to a robust solution to brain extraction from MRIs with pathologies, which do not exist in our training data set. We demonstrate the effectiveness of our networks by evaluating them on the OASIS data set, resulting in the state of the art performance under the two-fold cross-validation setting. Moreover, the robustness of our networks is verified by testing on images with introduced pathologies and by showing its invariance to unseen brain pathologies. In addition, our complementary network design is general and can be extended to address other image segmentation problems with better generalization.

##### Abstract (translated by Google)
脑提取是大多数脑成像研究的基本步骤。在本文中，我们调查颅骨剥离问题，并提出补充分割网络（CompNets），以正常和病理性脑部图像从T1加权MRI扫描中精确提取脑部。所提出的网络是在编码器 - 解码器网络的框架内设计的，并具有两种途径来从大脑组织及其位于大脑外的互补部分学习特征。补充路径提取非脑部区域的特征，并导致从具有病理的MRI中提取脑部的鲁棒解决方案，这在我们的训练数据集中不存在。我们通过在OASIS数据集上评估他们的网络来证明我们的网络的有效性，从而在双重交叉验证设置下获得最先进的性能。此外，我们的网络的鲁棒性通过对引入的病理图像进行测试并通过显示其对未见的脑病变的不变性来验证。另外，我们的互补网络设计是通用的，并且可以扩展到更好的通用化来解决其他图像分割问题。

##### URL
[http://arxiv.org/abs/1804.00521](http://arxiv.org/abs/1804.00521)

##### PDF
[http://arxiv.org/pdf/1804.00521](http://arxiv.org/pdf/1804.00521)

