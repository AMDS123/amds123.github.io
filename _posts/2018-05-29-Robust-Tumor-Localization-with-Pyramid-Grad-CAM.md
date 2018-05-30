---
layout: post
title: "Robust Tumor Localization with Pyramid Grad-CAM"
date: 2018-05-29 12:36:24
categories: arXiv_CV
tags: arXiv_CV Weakly_Supervised CNN Detection
author: Sungmin Lee, Jangho Lee, Jungbeom Lee, Chul-Kee Park, Sungroh Yoon
mathjax: true
---

* content
{:toc}

##### Abstract
A meningioma is a type of brain tumor that requires tumor volume size follow ups in order to reach appropriate clinical decisions. A fully automated tool for meningioma detection is necessary for reliable and consistent tumor surveillance. There have been various studies concerning automated lesion detection. Studies on the application of convolutional neural network (CNN)-based methods, which have achieved a state-of-the-art level of performance in various computer vision tasks, have been carried out. However, the applicable diseases are limited, owing to a lack of strongly annotated data being present in medical image analysis. In order to resolve the above issue we propose pyramid gradient-based class activation mapping (PG-CAM) which is a novel method for tumor localization that can be trained in weakly supervised manner. PG-CAM uses a densely connected encoder-decoder-based feature pyramid network (DC-FPN) as a backbone structure, and extracts a multi-scale Grad-CAM that captures hierarchical features of a tumor. We tested our model using meningioma brain magnetic resonance (MR) data collected from the collaborating hospital. In our experiments, PG-CAM outperformed Grad-CAM by delivering a 23 percent higher localization accuracy for the validation set.

##### Abstract (translated by Google)
脑膜瘤是一种需要肿瘤体积大小追踪以达到适当的临床决策的脑肿瘤。一个全自动的脑膜瘤检测工具对于可靠和一致的肿瘤监测是必不可少的。有关自动化病变检测的各种研究。已经开展了基于卷积神经网络（CNN）的方法的研究，这些方法已经在各种计算机视觉任务中达到了最高水平的性能。然而，由于医学图像分析中缺乏强烈注释的数据，所以适用的疾病是有限的。为了解决上述问题，我们提出了基于梯度的金字塔类激活映射（PG-CAM），这是一种肿瘤定位新方法，可以用弱监督方式进行训练。 PG-CAM使用密集连接的基于编码器 - 解码器的特征金字塔网络（DC-FPN）作为骨干结构，并提取捕获肿瘤的分层特征的多尺度Grad-CAM。我们使用从协作医院收集的脑膜瘤脑磁共振（MR）数据测试了我们的模型。在我们的实验中，PG-CAM通过为验证集提供高23％的定位精度而优于Grad-CAM。

##### URL
[http://arxiv.org/abs/1805.11393](http://arxiv.org/abs/1805.11393)

##### PDF
[http://arxiv.org/pdf/1805.11393](http://arxiv.org/pdf/1805.11393)

