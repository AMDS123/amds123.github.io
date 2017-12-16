---
layout: post
title: "High-Resolution Breast Cancer Screening with Multi-View Deep Convolutional Neural Networks"
date: 2017-11-06 06:39:33
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning Prediction Detection
author: Krzysztof J. Geras, Stacey Wolfson, Yiqiu Shen, S. Gene Kim, Linda Moy, Kyunghyun Cho
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advances in deep learning for natural images has prompted a surge of interest in applying similar techniques to medical images. Most of the initial attempts focused on replacing the input of a deep convolutional neural network with a medical image, which does not take into consideration the fundamental differences between these two types of images. Specifically, fine details are necessary for detection in medical images, unlike in natural images where coarse structures matter. This difference makes it inadequate to use the existing network architectures developed for natural images, because they work on an heavily downsampled image to reduce the memory requirements. This hides details necessary to make accurate predictions. Additionally, a single exam in medical imaging often comes with a set of views which must be fused in order to reach a correct conclusion. In our work, we propose to use a multi-view deep convolutional neural network that handles a set of high-resolution medical images. We evaluate it on large-scale mammography-based breast cancer screening (BI-RADS prediction) using 886 thousand images. We focus on investigating the impact of training set size and image size on the prediction accuracy. Our results highlight that performance increases with the size of training set, and that the best performance can only be achieved using the original resolution. This suggests that medical imaging research using deep learning must utilize as much data as possible with the least amount of potentially harmful preprocessing.

##### Abstract (translated by Google)
最近在自然图像的深度学习方面取得的进展促使人们对将相似的技术应用于医学图像感兴趣。最初的尝试主要集中于用医学图像替代深卷积神经网络的输入，而没有考虑这两种图像之间的根本区别。具体而言，与粗糙结构的自然图像不同，细节对于医学图像中的检测是必要的。这种差异使得使用为自然图像开发的现有网络体系结构是不够的，因为它们在严重下采样图像上工作以减少存储器需求。这隐藏了必要的细节做出准确的预测。另外，一个单一的医学影像考试往往带有一套必须融合的观点，才能得出正确的结论。在我们的工作中，我们建议使用处理一组高分辨率医学图像的多视点深度卷积神经网络。我们使用88.6万幅图像对大型乳房X线照相乳腺癌筛查（BI-RADS预测）进行评估。我们着重研究训练集大小和图像大小对预测精度的影响。我们的结果强调，性能随着训练集的大小而增加，并且只有使用原始分辨率才能获得最佳性能。这表明，使用深度学习的医学成像研究必须尽可能多地利用尽可能多的数据和最少量的可能有害的预处理。

##### URL
[https://arxiv.org/abs/1703.07047](https://arxiv.org/abs/1703.07047)

##### PDF
[https://arxiv.org/pdf/1703.07047](https://arxiv.org/pdf/1703.07047)

