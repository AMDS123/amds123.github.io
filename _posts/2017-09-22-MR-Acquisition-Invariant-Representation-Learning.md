---
layout: post
title: "MR Acquisition-Invariant Representation Learning"
date: 2017-09-22 20:52:14
categories: arXiv_CV
tags: arXiv_CV CNN Represenation_Learning Classification
author: Wouter M. Kouw, Marco Loog, Lambertus W. Bartels, Adriënne M. Mendrik
mathjax: true
---

* content
{:toc}

##### Abstract
Voxelwise classification is a popular and effective method for tissue quantification in brain magnetic resonance imaging (MRI) scans. However, there are often large differences over sets of MRI scans due to how they were acquired (i.e. field strength, vendor, protocol), that lead to variation in, among others, pixel intensities, tissue contrast, signal-to-noise ratio, resolution, slice thickness and magnetic field inhomogeneities. Classifiers trained on data from a specific scanner fail or under-perform when applied to data that was differently acquired. In order to address this lack of generalization, we propose a Siamese neural network (MRAI-net) to learn a representation that minimizes the between-scanner variation, while maintaining the contrast between brain tissues necessary for brain tissue quantification. The proposed MRAI-net was evaluated on both simulated and real MRI data. After learning the MR acquisition invariant representation, any supervised classifier can be applied. In this paper we showed that applying a linear classifier on the MRAI representation outperforms supervised convolutional neural network classifiers for tissue classification when little target training data is available.

##### Abstract (translated by Google)
体素分类是脑磁共振成像（MRI）扫描中组织定量的流行和有效的方法。然而，由于采集方式（即场强，供应商，协议），MRI扫描集合往往存在很大差异，导致像素强度，组织对比度，信噪比等变化。分辨率，切片厚度和磁场不均匀性。在应用于不同获取的数据时，针对特定扫描器的数据进行训练的分类器失败或执行不足。为了解决这种通用性的不足，我们提出了一个连体神经网络（MRAI-net）来学习一种表示，以最小化扫描仪之间的差异，同时保持脑组织量化所必需的脑组织之间的对比度。拟议的MRAI网在模拟和真实的MRI数据上进行评估。在学习MR获取不变表示之后，可以应用任何监督分类器。在本文中，我们表明，在MRAI表示上应用线性分类器时，当有少量的目标训练数据可用时，要比监督卷积神经网络分类器的组织分类更胜一筹。

##### URL
[https://arxiv.org/abs/1709.07944](https://arxiv.org/abs/1709.07944)

##### PDF
[https://arxiv.org/pdf/1709.07944](https://arxiv.org/pdf/1709.07944)

