---
layout: post
title: "Reinforced Auto-Zoom Net: Towards Accurate and Fast Breast Cancer Segmentation in Whole-slide Images"
date: 2018-07-29 21:45:35
categories: arXiv_AI
tags: arXiv_AI Segmentation CNN Inference Prediction
author: Nanqing Dong, Michael Kampffmeyer, Xiaodan Liang, Zeya Wang, Wei Dai, Eric P. Xing
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks have led to significant breakthroughs in the domain of medical image analysis. However, the task of breast cancer segmentation in whole-slide images (WSIs) is still underexplored. WSIs are large histopathological images with extremely high resolution. Constrained by the hardware and field of view, using high-magnification patches can slow down the inference process and using low-magnification patches can cause the loss of information. In this paper, we aim to achieve two seemingly conflicting goals for breast cancer segmentation: accurate and fast prediction. We propose a simple yet efficient framework Reinforced Auto-Zoom Net (RAZN) to tackle this task. Motivated by the zoom-in operation of a pathologist using a digital microscope, RAZN learns a policy network to decide whether zooming is required in a given region of interest. Because the zoom-in action is selective, RAZN is robust to unbalanced and noisy ground truth labels and can efficiently reduce overfitting. We evaluate our method on a public breast cancer dataset. RAZN outperforms both single-scale and multi-scale baseline approaches, achieving better accuracy at low inference cost.

##### Abstract (translated by Google)
卷积神经网络已经在医学图像分析领域取得了重大突破。然而，全幻灯片图像（WSI）中乳腺癌细分的任务仍未得到充分研究。 WSI是具有极高分辨率的大型组织病理学图像。受硬件和视野的限制，使用高放大率的补丁会减慢推理过程，并且使用低放大率补丁会导致信息丢失。在本文中，我们的目标是实现两个看似相互冲突的乳腺癌分割目标：准确和快速的预测。我们提出了一个简单而有效的框架强化自动缩放网络（RAZN）来解决这个问题。通过使用数字显微镜的病理学家的放大操作的动机，RAZN学习策略网络以决定在给定的感兴趣区域中是否需要缩放。由于放大动作是选择性的，因此RAZN对不平衡和嘈杂的地面实况标签很稳健，并且可以有效地减少过度拟合。我们在公共乳腺癌数据集上评估我们的方法。 RAZN优于单尺度和多尺度基线方法，在低推理成本下实现更高的精度。

##### URL
[http://arxiv.org/abs/1807.11113](http://arxiv.org/abs/1807.11113)

##### PDF
[http://arxiv.org/pdf/1807.11113](http://arxiv.org/pdf/1807.11113)

