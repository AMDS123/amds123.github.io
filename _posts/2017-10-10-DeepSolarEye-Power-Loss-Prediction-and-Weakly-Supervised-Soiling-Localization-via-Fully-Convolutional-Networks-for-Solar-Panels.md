---
layout: post
title: "DeepSolarEye: Power Loss Prediction and Weakly Supervised Soiling Localization via Fully Convolutional Networks for Solar Panels"
date: 2017-10-10 20:31:42
categories: arXiv_CV
tags: arXiv_CV Segmentation Weakly_Supervised CNN Prediction
author: Sachin Mehta, Amar P. Azad, Saneem A. Chemmengath, Vikas Raykar, Shivkumar Kalyanraman
mathjax: true
---

* content
{:toc}

##### Abstract
Impact of soiling on solar panels is an important and well-studied problem in renewable energy sector. In this paper, we present a novel approach based on fully convolutional networks which takes an RGB image of solar panel and environmental factors (optional) as inputs to predict power loss, soiling localization, and soiling type. In computer vision, predicting localization is a complex task which typically requires human labeled data such as bounding boxes or segmentation masks. Our proposed approach consists of specialized four stages which completely avoids human labeled localization data and only needs panel images with power loss for training. The region of impact area obtained from the localization masks are then classified into soiling types using the webly supervised learning. For superior localization capabilities of convolutional neural networks (CNNs), we introduce a novel bi-directional input-aware fusion (BiDIAF) block that reinforces the input at different levels of CNN to learn input-specific feature maps. Our empirical study shows that BiDIAF improves the power loss prediction accuracy and the localization Jaccard index of ResNet by about 3% and 4% respectively. Our end-to-end model yields further improvement of about 24% on localization task when learned in a weakly supervised manner. Our approach is generalizable and showed promising results on web crawled solar panel images. Additionally, we collected first of it's kind dataset for solar panel image analysis consisting 45,000+ images.

##### Abstract (translated by Google)
污染对太阳能电池板的影响是可再生能源领域中一个重要和深入研究的问题。在本文中，我们提出了一种基于完全卷积网络的新方法，该方法以太阳能电池板的RGB图像和环境因素（可选）作为输入来预测功率损失，污染定位和污染类型。在计算机视觉中，预测本地化是一个复杂的任务，通常需要人类标记的数据，如边界框或分割掩码。我们提出的方法包括专门的四个阶段，完全避免了人类标记的定位数据，只需要面板图像与功率损失的培训。然后使用网络监督学习将从定位蒙版获得的影响区域分类为污染类型。为了提高卷积神经网络（CNN）的定位能力，我们引入了一种新颖的双向输入感知融合（BiDIAF）模块，加强了CNN不同层次的输入，以学习输入特定的特征映射。我们的实证研究表明，BiDIAF将ResNet的功率损耗预测精度和定位Jaccard指数分别提高了约3％和4％。我们的端到端模式在以弱监督的方式学习时，可以进一步提高本地化任务的24％。我们的方法是可普遍化的，并且在网页爬行太阳能电池板图像上显示出有希望的结果此外，我们收集了第一个太阳能电池板图像分析数据集，包含45,000多张图像。

##### URL
[https://arxiv.org/abs/1710.03811](https://arxiv.org/abs/1710.03811)

##### PDF
[https://arxiv.org/pdf/1710.03811](https://arxiv.org/pdf/1710.03811)

