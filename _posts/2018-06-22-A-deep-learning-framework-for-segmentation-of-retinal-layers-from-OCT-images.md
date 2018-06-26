---
layout: post
title: "A deep learning framework for segmentation of retinal layers from OCT images"
date: 2018-06-22 21:24:58
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN RNN Deep_Learning Detection
author: Karthik Gopinath, Samrudhdhi B Rangrej, Jayanthi Sivaswamy
mathjax: true
---

* content
{:toc}

##### Abstract
Segmentation of retinal layers from Optical Coherence Tomography (OCT) volumes is a fundamental problem for any computer aided diagnostic algorithm development. This requires preprocessing steps such as denoising, region of interest extraction, flattening and edge detection all of which involve separate parameter tuning. In this paper, we explore deep learning techniques to automate all these steps and handle the presence/absence of pathologies. A model is proposed consisting of a combination of Convolutional Neural Network (CNN) and Long Short Term Memory (LSTM). The CNN is used to extract layers of interest image and extract the edges, while the LSTM is used to trace the layer boundary. This model is trained on a mixture of normal and AMD cases using minimal data. Validation results on three public datasets show that the pixel-wise mean absolute error obtained with our system is 1.30 plus or minus 0.48 which is lower than the inter-marker error of 1.79 plus or minus 0.76. Our model's performance is also on par with the existing methods.

##### Abstract (translated by Google)
从光学相干断层扫描（OCT）体积分割视网膜层是任何计算机辅助诊断算法开发的基本问题。这需要预处理步骤，例如去噪，感兴趣区域提取，平坦化和边缘检测，所有这些都涉及单独的参数调整。在本文中，我们探索深度学习技术，使所有这些步骤自动化，并处理存在/不存在病理。提出了一种由卷积神经网络（CNN）和长期短期记忆（LSTM）组成的模型。 CNN用于提取感兴趣的图像并提取边缘，而LSTM用于跟踪图层边界。使用最少的数据对该模型进行正常和AMD病例的混合培训。对三个公共数据集的验证结果显示，我们的系统获得的像素平均绝对误差为1.30±0.48，低于1.79±0.76的标记间误差。我们的模型的性能也与现有方法一致。

##### URL
[http://arxiv.org/abs/1806.08859](http://arxiv.org/abs/1806.08859)

##### PDF
[http://arxiv.org/pdf/1806.08859](http://arxiv.org/pdf/1806.08859)

