---
layout: post
title: "Saliency Detection via Combining Region-Level and Pixel-Level Predictions with CNNs"
date: 2016-08-18 06:00:18
categories: arXiv_CV
tags: arXiv_CV Salient CNN Prediction Quantitative Detection
author: Youbao Tang, Xiangqian Wu
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a novel saliency detection method by combining region-level saliency estimation and pixel-level saliency prediction with CNNs (denoted as CRPSD). For pixel-level saliency prediction, a fully convolutional neural network (called pixel-level CNN) is constructed by modifying the VGGNet architecture to perform multi-scale feature learning, based on which an image-to-image prediction is conducted to accomplish the pixel-level saliency detection. For region-level saliency estimation, an adaptive superpixel based region generation technique is first designed to partition an image into regions, based on which the region-level saliency is estimated by using a CNN model (called region-level CNN). The pixel-level and region-level saliencies are fused to form the final salient map by using another CNN (called fusion CNN). And the pixel-level CNN and fusion CNN are jointly learned. Extensive quantitative and qualitative experiments on four public benchmark datasets demonstrate that the proposed method greatly outperforms the state-of-the-art saliency detection approaches.

##### Abstract (translated by Google)
本文提出了一种结合区域级显着性估计和像素级显着性预测与CNNs（表示为CRPSD）的显着性检测方法。对于像素级显着性预测，通过修改VGGNet架构进行多尺度特征学习，构建完全卷积神经网络（称为像素级CNN），在此基础上进行图像间预测以完成像素级显着性检测。对于区域级显着性估计，首先设计一种基于自适应超像素的区域生成技术，将图像划分为多个区域，基于该区域级显着性通过CNN模型（称为区域级CNN）进行估计。通过使用另一个CNN（称为融合CNN）将像素级和区域级显着性融合以形成最终的显着图。像素级CNN和融合CNN是共同学习的。在四个公共基准数据集上进行大量的定量和定性实验表明，所提出的方法大大优于最先进的显着性检测方法。

##### URL
[https://arxiv.org/abs/1608.05186](https://arxiv.org/abs/1608.05186)

##### PDF
[https://arxiv.org/pdf/1608.05186](https://arxiv.org/pdf/1608.05186)

