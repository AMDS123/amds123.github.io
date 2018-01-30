---
layout: post
title: "DeepLung: Deep 3D Dual Path Nets for Automated Pulmonary Nodule Detection and Classification"
date: 2018-01-25 23:22:00
categories: arXiv_CV
tags: arXiv_CV CNN Classification Detection
author: Wentao Zhu, Chaochun Liu, Wei Fan, Xiaohui Xie
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we present a fully automated lung computed tomography (CT) cancer diagnosis system, DeepLung. DeepLung consists of two components, nodule detection (identifying the locations of candidate nodules) and classification (classifying candidate nodules into benign or malignant). Considering the 3D nature of lung CT data and the compactness of dual path networks (DPN), two deep 3D DPN are designed for nodule detection and classification respectively. Specifically, a 3D Faster Regions with Convolutional Neural Net (R-CNN) is designed for nodule detection with 3D dual path blocks and a U-net-like encoder-decoder structure to effectively learn nodule features. For nodule classification, gradient boosting machine (GBM) with 3D dual path network features is proposed. The nodule classification subnetwork was validated on a public dataset from LIDC-IDRI, on which it achieved better performance than state-of-the-art approaches and surpassed the performance of experienced doctors based on image modality. Within the DeepLung system, candidate nodules are detected first by the nodule detection subnetwork, and nodule diagnosis is conducted by the classification subnetwork. Extensive experimental results demonstrate that DeepLung has performance comparable to experienced doctors both for the nodule-level and patient-level diagnosis on the LIDC-IDRI dataset.\footnote{https://github.com/uci-cbcl/DeepLung.git}

##### Abstract (translated by Google)
在这项工作中，我们提出了一个全自动的肺部计算机断层扫描（CT）癌症诊断系统DeepLung。 DeepLung由两部分组成，结节检测（确定候选结节的位置）和分类（将候选结节分类为良性或恶性）。考虑到肺部CT数据的三维性质和双路径网络（DPN）的紧凑性，分别设计了两个深度三维DPN用于结节检测和分类。具体来说，设计了一个带有卷积神经网络（R-CNN）的三维快速区域，用于三维双路径块和U-net-like编码器 - 解码器结构的结节检测，以有效地学习结节特征。对于结核分类，提出了具有3D双路径网络特征的梯度提升机（GBM）。根据LIDC-IDRI公开的数据集对结节分类子网络进行验证，在该数据集上获得了比现有技术更好的性能，并且超过了基于图像形态的有经验的医生的表现。在DeepLung系统中，结节检测子网首先检测候选结节，结节诊断由分类子网进行。广泛的实验结果表明DeepLung在LIDC-IDRI数据集中具有与经验丰富的医生相媲美的性能。\ footnote {https://github.com/uci-cbcl/DeepLung.git}

##### URL
[http://arxiv.org/abs/1801.09555](http://arxiv.org/abs/1801.09555)

##### PDF
[http://arxiv.org/pdf/1801.09555](http://arxiv.org/pdf/1801.09555)

