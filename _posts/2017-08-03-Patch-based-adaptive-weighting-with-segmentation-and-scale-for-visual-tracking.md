---
layout: post
title: "Patch-based adaptive weighting with segmentation and scale for visual tracking"
date: 2017-08-03 15:19:27
categories: arXiv_CV
tags: arXiv_CV Segmentation Tracking Object_Tracking Classification Detection
author: Xiaofei Du, Alessio Dore, Danail Stoyanov
mathjax: true
---

* content
{:toc}

##### Abstract
Tracking-by-detection algorithms are widely used for visual tracking, where the problem is treated as a classification task where an object model is updated over time using online learning techniques. In challenging conditions where an object undergoes deformation or scale variations, the update step is prone to include background information in the model appearance or to lack the ability to estimate the scale change, which degrades the performance of the classifier. In this paper, we incorporate a Patch-based Adaptive Weighting with Segmentation and Scale (PAWSS) tracking framework that tackles both the scale and background problems. A simple but effective colour-based segmentation model is used to suppress background information and multi-scale samples are extracted to enrich the training pool, which allows the tracker to handle both incremental and abrupt scale variations between frames. Experimentally, we evaluate our approach on the online tracking benchmark (OTB) dataset and Visual Object Tracking (VOT) challenge datasets. The results show that our approach outperforms recent state-of-the-art trackers, and it especially improves the successful rate score on the OTB dataset, while on the VOT datasets, PAWSS ranks among the top trackers while operating at real-time frame rates.

##### Abstract (translated by Google)
跟踪检测算法被广泛用于视觉跟踪，其中问题被视为一个分类任务，其中一个对象模型随着时间的推移使用在线学习技术进行更新。在对象经历变形或尺度变化的具有挑战性的情况下，更新步骤倾向于在模型外观中包括背景信息或缺乏估计尺度变化的能力，这降低了分类器的性能。在本文中，我们将基于补丁的自适应加权与分割和缩放（PAWSS）跟踪框架结合起来，以解决规模和背景问题。一个简单而有效的基于颜色的分割模型被用于抑制背景信息，并且提取多尺度样本以丰富训练池，这使得跟踪器能够处理帧之间的增量和突变尺度变化。在实验上，我们评估我们的在线跟踪基准（OTB）数据集和视觉对象跟踪（VOT）挑战数据集的方法。结果表明，我们的方法胜过了最近的最先进的跟踪器，它特别提高了OTB数据集的成功率评分，而在VOT数据集上，PAWSS在实时帧速率。

##### URL
[https://arxiv.org/abs/1708.01179](https://arxiv.org/abs/1708.01179)

##### PDF
[https://arxiv.org/pdf/1708.01179](https://arxiv.org/pdf/1708.01179)

