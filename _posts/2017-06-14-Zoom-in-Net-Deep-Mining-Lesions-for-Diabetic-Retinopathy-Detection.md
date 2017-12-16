---
layout: post
title: "Zoom-in-Net: Deep Mining Lesions for Diabetic Retinopathy Detection"
date: 2017-06-14 09:13:52
categories: arXiv_CV
tags: arXiv_CV Attention CNN Detection
author: Zhe Wang, Yanxin Yin, Jianping Shi, Wei Fang, Hongsheng Li, Xiaogang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a convolution neural network based algorithm for simultaneously diagnosing diabetic retinopathy and highlighting suspicious regions. Our contributions are two folds: 1) a network termed Zoom-in-Net which mimics the zoom-in process of a clinician to examine the retinal images. Trained with only image-level supervisions, Zoomin-Net can generate attention maps which highlight suspicious regions, and predicts the disease level accurately based on both the whole image and its high resolution suspicious patches. 2) Only four bounding boxes generated from the automatically learned attention maps are enough to cover 80% of the lesions labeled by an experienced ophthalmologist, which shows good localization ability of the attention maps. By clustering features at high response locations on the attention maps, we discover meaningful clusters which contain potential lesions in diabetic retinopathy. Experiments show that our algorithm outperform the state-of-the-art methods on two datasets, EyePACS and Messidor.

##### Abstract (translated by Google)
我们提出了一种基于卷积神经网络的算法来同时诊断糖尿病视网膜病变和突出可疑区域。我们的贡献有两个方面：1）称为放大网的网络模拟临床医生的放大过程以检查视网膜图像。 Zoomin-Net只经过图像级别的训练，可以生成突出可疑区域的注意图，并根据整个图像及其高分辨率的可疑色块准确预测疾病级别。 2）自动学习的注意力图所产生的边界框只有四个，足以覆盖有经验的眼科医生标注的80％的病灶，注意力图具有良好的定位能力。通过在注意图上的高响应位置聚类特征，我们发现含有潜在的糖尿病视网膜病变损害的有意义的聚类。实验表明，我们的算法在两个数据集EyePACS和Messidor上优于最先进的方法。

##### URL
[https://arxiv.org/abs/1706.04372](https://arxiv.org/abs/1706.04372)

##### PDF
[https://arxiv.org/pdf/1706.04372](https://arxiv.org/pdf/1706.04372)

