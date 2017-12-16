---
layout: post
title: "DeepLung: 3D Deep Convolutional Nets for Automated Pulmonary Nodule Detection and Classification"
date: 2017-09-16 16:18:22
categories: arXiv_CV
tags: arXiv_CV CNN Classification Detection
author: Wentao Zhu, Chaochun Liu, Wei Fan, Xiaohui Xie
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we present a fully automated lung CT cancer diagnosis system, DeepLung. DeepLung contains two parts, nodule detection and classification. Considering the 3D nature of lung CT data, two 3D networks are designed for the nodule detection and classification respectively. Specifically, a 3D Faster R-CNN is designed for nodule detection with a U-net-like encoder-decoder structure to effectively learn nodule features. For nodule classification, gradient boosting machine (GBM) with 3D dual path network (DPN) features is proposed. The nodule classification subnetwork is validated on a public dataset from LIDC-IDRI, on which it achieves better performance than state-of-the-art approaches, and surpasses the average performance of four experienced doctors. For the DeepLung system, candidate nodules are detected first by the nodule detection subnetwork, and nodule diagnosis is conducted by the classification subnetwork. Extensive experimental results demonstrate the DeepLung is comparable to the experienced doctors both for the nodule-level and patient-level diagnosis on the LIDC-IDRI dataset.

##### Abstract (translated by Google)
在这项工作中，我们提出了一个完全自动化的肺癌CT诊断系统DeepLung。 DeepLung包含两个部分，结核检测和分类。考虑到肺部CT数据的三维性，分别设计了两个三维网络进行结节检测和分类。具体来说，一个3D快速R-CNN被设计用于类似U-net的编码器 - 解码器结构的结节检测，以有效地学习结节特征。对于结核分类，提出了具有3D双路径网络（DPN）特征的梯度提升机（GBM）。结节分类子网在来自LIDC-IDRI的公共数据集上进行验证，在这个公共数据集上获得比现有技术更好的性能，并且超过了四位有经验的医生的平均表现。对于DeepLung系统，首先由结节检测子网络检测候选结节，结节诊断由分类子网络进行。广泛的实验结果表明，DeepLung与LIDC-IDRI数据集的结节水平和患者水平诊断相媲美。

##### URL
[https://arxiv.org/abs/1709.05538](https://arxiv.org/abs/1709.05538)

##### PDF
[https://arxiv.org/pdf/1709.05538](https://arxiv.org/pdf/1709.05538)

