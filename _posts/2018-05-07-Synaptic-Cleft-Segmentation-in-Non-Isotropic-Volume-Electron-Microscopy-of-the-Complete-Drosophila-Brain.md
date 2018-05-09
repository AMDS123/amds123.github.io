---
layout: post
title: "Synaptic Cleft Segmentation in Non-Isotropic Volume Electron Microscopy of the Complete Drosophila Brain"
date: 2018-05-07 19:48:19
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN Prediction
author: Larissa Heinrich, Jan Funke, Constantin Pape, Juan Nunez-Iglesias, Stephan Saalfeld
mathjax: true
---

* content
{:toc}

##### Abstract
Neural circuit reconstruction at single synapse resolution is increasingly recognized as crucially important to decipher the function of biological nervous systems. Volume electron microscopy in serial transmission or scanning mode has been demonstrated to provide the necessary resolution to segment or trace all neurites and to annotate all synaptic connections. Automatic annotation of synaptic connections has been done successfully in near isotropic electron microscopy of vertebrate model organisms. Results on non-isotropic data in insect models, however, are not yet on par with human annotation. We designed a new 3D-U-Net architecture to optimally represent isotropic fields of view in non-isotropic data. We used regression on a signed distance transform of manually annotated synaptic clefts of the CREMI challenge dataset to train this model and observed significant improvement over the state of the art. We developed open source software for optimized parallel prediction on very large volumetric datasets and applied our model to predict synaptic clefts in a 50 tera-voxels dataset of the complete Drosophila brain. Our model generalizes well to areas far away from where training data was available.

##### Abstract (translated by Google)
人们越来越认识到单突触分辨率下的神经回路重建对于破译生物神经系统的功能至关重要。已经证明串行传输或扫描模式下的体积电子显微镜提供了分割或追踪所有神经突并标注所有突触连接的必要分辨率。自动注释的突触连接已成功完成近脊椎动物模型生物各向同性电子显微镜。然而，昆虫模型中的非各向同性数据的结果还没有与人类的注释相提并论。我们设计了一种新的3D-U-Net架构，以优化地表示非各向同性数据中的各向同性视场。我们使用CREMI挑战数据集的手动注释突触间隙的带符号距离变换的回归来训练该模型，并观察到对现有技术的显着改进。我们开发了开源软件，用于在非常大的体积数据集上优化并行预测，并应用我们的模型预测完整果蝇大脑的50 tera-voxels数据集中的突触间隙。我们的模型适用于远离训练数据可用的地方。

##### URL
[https://arxiv.org/abs/1805.02718](https://arxiv.org/abs/1805.02718)

##### PDF
[https://arxiv.org/pdf/1805.02718](https://arxiv.org/pdf/1805.02718)

