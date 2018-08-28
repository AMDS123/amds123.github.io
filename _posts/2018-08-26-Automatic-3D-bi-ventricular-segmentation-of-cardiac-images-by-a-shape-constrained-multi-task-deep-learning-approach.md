---
layout: post
title: "Automatic 3D bi-ventricular segmentation of cardiac images by a shape-constrained multi-task deep learning approach"
date: 2018-08-26 15:42:50
categories: arXiv_AI
tags: arXiv_AI Segmentation Attention CNN Deep_Learning
author: Jinming Duan, Ghalib Bello, Jo Schlemper, Wenjia Bai, Timothy J W Dawes, Carlo Biffi, \\Antonio de Marvao, Georgia Doumou, Declan P O&#x27;Regan, Daniel Rueckert
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning approaches have achieved state-of-the-art performance in cardiac magnetic resonance (CMR) image segmentation. However, most approaches have focused on learning image intensity features for segmentation, whereas the incorporation of anatomical shape priors has received less attention. In this paper, we combine a multi-task deep learning approach with atlas propagation to develop a shape-constrained bi-ventricular segmentation pipeline for short-axis CMR volumetric images. The pipeline first employs a fully convolutional network (FCN) that learns segmentation and landmark localisation tasks simultaneously. The architecture of the proposed FCN uses a 2.5D representation, thus combining the computational advantage of 2D FCNs networks and the capability of addressing 3D spatial consistency without compromising segmentation accuracy. Moreover, the refinement step is designed to explicitly enforce a shape constraint and improve segmentation quality. This step is effective for overcoming image artefacts (e.g. due to different breath-hold positions and large slice thickness), which preclude the creation of anatomically meaningful 3D cardiac shapes. The proposed pipeline is fully automated, due to network's ability to infer landmarks, which are then used downstream in the pipeline to initialise atlas propagation. We validate the pipeline on 1831 healthy subjects and 649 subjects with pulmonary hypertension. Extensive numerical experiments on the two datasets demonstrate that our proposed method is robust and capable of producing accurate, high-resolution and anatomically smooth bi-ventricular 3D models, despite the artefacts in input CMR volumes.

##### Abstract (translated by Google)
深度学习方法在心脏磁共振（CMR）图像分割中实现了最先进的性能。然而，大多数方法都集中在学习用于分割的图像强度特征，而解剖学形状先验的结合受到较少关注。在本文中，我们将多任务深度学习方法与图谱传播相结合，为短轴CMR体积图像开发形状受限的双心室分割管道。该管道首先采用完全卷积网络（FCN），同时学习分段和地标定位任务。所提出的FCN的体系结构使用2.5D表示，因此结合了2D FCN网络的计算优势和解决3D空间一致性的能力而不损害分割准确性。此外，细化步骤旨在明确地实施形状约束并提高分割质量。该步骤对于克服图像伪影（例如，由于不同的屏气位置和大的切片厚度）是有效的，这阻止了解剖学上有意义的3D心脏形状的产生。建议的管道是完全自动化的，因为网络能够推断地标，然后在管道的下游用于初始化地图集传播。我们验证了1831名健康受试者和649名肺动脉高压患者的管道。对这两个数据集的广泛数值实验表明，尽管输入CMR体积中存在假象，但我们提出的方法是稳健的并且能够产生精确的，高分辨率和解剖学上平滑的双心室3D模型。

##### URL
[http://arxiv.org/abs/1808.08578](http://arxiv.org/abs/1808.08578)

##### PDF
[http://arxiv.org/pdf/1808.08578](http://arxiv.org/pdf/1808.08578)

