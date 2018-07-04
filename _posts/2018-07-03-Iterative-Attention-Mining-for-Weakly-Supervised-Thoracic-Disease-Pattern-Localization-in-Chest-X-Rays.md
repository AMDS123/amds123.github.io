---
layout: post
title: "Iterative Attention Mining for Weakly Supervised Thoracic Disease Pattern Localization in Chest X-Rays"
date: 2018-07-03 02:56:38
categories: arXiv_CV
tags: arXiv_CV Salient Knowledge Attention Weakly_Supervised CNN Image_Classification Classification Prediction
author: Jinzheng Cai, Le Lu, Adam P. Harrison, Xiaoshuang Shi, Pingjun Chen, Lin Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Given image labels as the only supervisory signal, we focus on harvesting, or mining, thoracic disease localizations from chest X-ray images. Harvesting such localizations from existing datasets allows for the creation of improved data sources for computer-aided diagnosis and retrospective analyses. We train a convolutional neural network (CNN) for image classification and propose an attention mining (AM) strategy to improve the model's sensitivity or saliency to disease patterns. The intuition of AM is that once the most salient disease area is blocked or hidden from the CNN model, it will pay attention to alternative image regions, while still attempting to make correct predictions. However, the model requires to be properly constrained during AM, otherwise, it may overfit to uncorrelated image parts and forget the valuable knowledge that it has learned from the original image classification task. To alleviate such side effects, we then design a knowledge preservation (KP) loss, which minimizes the discrepancy between responses for X-ray images from the original and the updated networks. Furthermore, we modify the CNN model to include multi-scale aggregation (MSA), improving its localization ability on small-scale disease findings, e.g., lung nodules. We experimentally validate our method on the publicly-available ChestX-ray14 dataset, outperforming a class activation map (CAM)-based approach, and demonstrating the value of our novel framework for mining disease locations.

##### Abstract (translated by Google)
鉴于图像标签是唯一的监控信号，我们专注于从胸部X射线图像中采集或挖掘胸部疾病定位。从现有数据集中收集此类本地化允许创建用于计算机辅助诊断和回顾性分析的改进数据源。我们训练卷积神经网络（CNN）进行图像分类，并提出一种注意力挖掘（AM）策略，以提高模型对疾病模式的敏感性或显着性。 AM的直觉是，一旦最显着的疾病区域被CNN模型阻挡或隐藏，它将关注替代图像区域，同时仍试图做出正确的预测。然而，该模型需要在AM期间被适当地约束，否则，它可能过度拟合到不相关的图像部分并且忘记它从原始图像分类任务中学到的有价值的知识。为了减轻这种副作用，我们设计了知识保存（KP）损失，这使得来自原始网络和更新网络的X射线图像的响应之间的差异最小化。此外，我们修改CNN模型以包括多尺度聚集（MSA），改善其对小规模疾病发现（例如肺结节）的定位能力。我们在公开可用的ChestX-ray14数据集上实验验证了我们的方法，优于基于类激活图（CAM）的方法，并证明了我们用于挖掘疾病位置的新框架的价值。

##### URL
[https://arxiv.org/abs/1807.00958](https://arxiv.org/abs/1807.00958)

##### PDF
[https://arxiv.org/pdf/1807.00958](https://arxiv.org/pdf/1807.00958)

