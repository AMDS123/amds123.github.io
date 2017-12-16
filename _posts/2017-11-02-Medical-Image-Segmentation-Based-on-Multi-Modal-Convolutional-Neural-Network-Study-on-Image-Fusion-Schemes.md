---
layout: post
title: "Medical Image Segmentation Based on Multi-Modal Convolutional Neural Network: Study on Image Fusion Schemes"
date: 2017-11-02 16:02:28
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Deep_Learning
author: Zhe Guo, Xiang Li, Heng Huang, Ning Guo, Quanzheng Li
mathjax: true
---

* content
{:toc}

##### Abstract
Image analysis using more than one modality (i.e. multi-modal) has been increasingly applied in the field of biomedical imaging. One of the challenges in performing the multimodal analysis is that there exist multiple schemes for fusing the information from different modalities, where such schemes are application-dependent and lack a unified framework to guide their designs. In this work we firstly propose a conceptual architecture for the image fusion schemes in supervised biomedical image analysis: fusing at the feature level, fusing at the classifier level, and fusing at the decision-making level. Further, motivated by the recent success in applying deep learning for natural image analysis, we implement the three image fusion schemes above based on the Convolutional Neural Network (CNN) with varied structures, and combined into a single framework. The proposed image segmentation framework is capable of analyzing the multi-modality images using different fusing schemes simultaneously. The framework is applied to detect the presence of soft tissue sarcoma from the combination of Magnetic Resonance Imaging (MRI), Computed Tomography (CT) and Positron Emission Tomography (PET) images. It is found from the results that while all the fusion schemes outperform the single-modality schemes, fusing at the feature level can generally achieve the best performance in terms of both accuracy and computational cost, but also suffers from the decreased robustness in the presence of large errors in any image modalities.

##### Abstract (translated by Google)
使用多种模态（即多模态）的图像分析已越来越多地应用于生物医学成像领域。执行多模式分析所面临的挑战之一是，存在多种方案来融合来自不同模式的信息，其中这些方案是依赖于应用的，并且缺乏统一的框架来指导其设计。在这项工作中，我们首先提出了一个监督生物医学图像分析中的图像融合方案的概念架构：在特征层融合，在分类器层融合，在决策层融合。此外，由于最近成功应用深度学习进行自然图像分析，我们实现了基于卷积神经网络（CNN）的上述三种不同结构的图像融合方案，并将其组合成一个单一的框架。所提出的图像分割框架能够同时使用不同的融合方案来分析多模态图像。该框架被用于检测来自磁共振成像（MRI），计算机断层扫描（CT）和正电子发射断层扫描（PET）图像组合的软组织肉瘤的存在。从结果中可以发现，虽然所有的融合方案都优于单模态方案，但是在特征水平上的融合一般可以在精度和计算成本方面达到最佳性能，但是也存在任何图像模式中的大错误。

##### URL
[https://arxiv.org/abs/1711.00049](https://arxiv.org/abs/1711.00049)

##### PDF
[https://arxiv.org/pdf/1711.00049](https://arxiv.org/pdf/1711.00049)

