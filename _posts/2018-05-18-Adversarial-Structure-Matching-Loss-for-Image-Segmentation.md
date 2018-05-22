---
layout: post
title: "Adversarial Structure Matching Loss for Image Segmentation"
date: 2018-05-18 22:03:58
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation Image_Classification Semantic_Segmentation Classification Prediction
author: Jyh-Jing Hwang, Tsung-Wei Ke, Jianbo Shi, Stella X. Yu
mathjax: true
---

* content
{:toc}

##### Abstract
The per-pixel cross-entropy loss (CEL) has been widely used in structured output prediction tasks as a spatial extension of generic image classification. However, its i.i.d. assumption neglects the structural regularity present in natural images. Various attempts have been made to incorporate structural reasoning mostly through structure priors in a cooperative way where co-occuring patterns are encouraged. We, on the other hand, approach this problem from an opposing angle and propose a new framework for training such structured prediction networks via an adversarial process, in which we train a structure analyzer that provides the supervisory signals, the adversarial structure matching loss (ASML). The structure analyzer is trained to maximize ASML, or to exaggerate recurring structural mistakes usually among co-occurring patterns. On the contrary, the structured output prediction network is trained to reduce those mistakes and is thus enabled to distinguish fine-grained structures. As a result, training structured output prediction networks using ASML reduces contextual confusion among objects and improves boundary localization. We demonstrate that ASML outperforms its counterpart CEL especially in context and boundary aspects on figure-ground segmentation and semantic segmentation tasks with various base architectures, such as FCN, U-Net, DeepLab, and PSPNet.

##### Abstract (translated by Google)
每像素交叉熵损失（CEL）已被广泛用于结构化输出预测任务中，作为通用图像分类的空间扩展。但是，它的i.i.d.假设忽略了自然图像中存在的结构规律性。已经进行了各种尝试，将结构推理纳入主要通过结构先验以合作方式鼓励共同发生模式。另一方面，我们从相反的角度来解决这个问题，并提出了一种新的框架，通过对抗过程来训练这种结构化预测网络，其中我们训练提供监督信号的结构分析器，对抗结构匹配损失（ASML ）。训练结构分析器以最大化ASML，或通常在共同出现的模式中夸大反复出现的结构错误。相反，结构化输出预测网络经过训练可以减少这些错误，从而可以区分细粒结构。因此，使用ASML对结构化输出预测网络进行训练可以减少对象间的上下文混淆并改善边界本地化。我们证明，ASML优于其对应的CEL，特别是在上下文和边界方面，用FCN，U-Net，DeepLab和PSPNet等各种基础体系结构进行图形地形分割和语义分割任务。

##### URL
[https://arxiv.org/abs/1805.07457](https://arxiv.org/abs/1805.07457)

##### PDF
[https://arxiv.org/pdf/1805.07457](https://arxiv.org/pdf/1805.07457)

