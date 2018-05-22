---
layout: post
title: "Learning Pixel-wise Labeling from the Internet without Human Interaction"
date: 2018-05-19 08:33:04
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention CNN Semantic_Segmentation Deep_Learning Prediction
author: Yun Liu, Yujun Shi, JiaWang Bian, Le Zhang, Ming-Ming Cheng, Jiashi Feng
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning stands at the forefront in many computer vision tasks. However, deep neural networks are usually data-hungry and require a huge amount of well-annotated training samples. Collecting sufficient annotated data is very expensive in many applications, especially for pixel-level prediction tasks such as semantic segmentation. To solve this fundamental issue, we consider a new challenging vision task, Internetly supervised semantic segmentation, which only uses Internet data with noisy image-level supervision of corresponding query keywords for segmentation model training. We address this task by proposing the following solution. A class-specific attention model unifying multiscale forward and backward convolutional features is proposed to provide initial segmentation "ground truth". The model trained with such noisy annotations is then improved by an online fine-tuning procedure. It achieves state-of-the-art performance under the weakly-supervised setting on PASCAL VOC2012 dataset. The proposed framework also paves a new way towards learning from the Internet without human interaction and could serve as a strong baseline therein. Code and data will be released upon the paper acceptance.

##### Abstract (translated by Google)
深度学习在许多计算机视觉任务中处于最前沿。然而，深度神经网络通常需要数据，需要大量注释良好的训练样本。在许多应用程序中收集足够的注释数据非常昂贵，特别是像语义分割等像素级预测任务。为了解决这个基本问题，我们考虑了一个新的具有挑战性的视觉任务，即互联网监督语义分割，它只使用互联网数据和噪声图像层监督相应的查询关键词进行分割模型训练。我们通过提出以下解决方案来解决此任务。提出了一种统一多尺度前向和后向卷积特征的类特定关注模型，以提供初始分割“基本事实”。用这种噪音标注进行训练的模型然后通过在线微调程序进行改进。它在PASCAL VOC2012数据集的弱监督环境下实现了最先进的性能。所提出的框架还为在没有人际交往的情况下从互联网学习提供了新的途径，并且可以作为其中的强有力基准。代码和数据将在接受论文后发布。

##### URL
[https://arxiv.org/abs/1805.07548](https://arxiv.org/abs/1805.07548)

##### PDF
[https://arxiv.org/pdf/1805.07548](https://arxiv.org/pdf/1805.07548)

