---
layout: post
title: "Estimation of the volume of the left ventricle from MRI images using deep neural networks"
date: 2017-02-13 15:43:52
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation GAN CNN Prediction Detection
author: Fangzhou Liao, Xi Chen, Xiaolin Hu, Sen Song
mathjax: true
---

* content
{:toc}

##### Abstract
Segmenting human left ventricle (LV) in magnetic resonance imaging (MRI) images and calculating its volume are important for diagnosing cardiac diseases. In 2016, Kaggle organized a competition to estimate the volume of LV from MRI images. The dataset consisted of a large number of cases, but only provided systole and diastole volumes as labels. We designed a system based on neural networks to solve this problem. It began with a detector combined with a neural network classifier for detecting regions of interest (ROIs) containing LV chambers. Then a deep neural network named hypercolumns fully convolutional network was used to segment LV in ROIs. The 2D segmentation results were integrated across different images to estimate the volume. With ground-truth volume labels, this model was trained end-to-end. To improve the result, an additional dataset with only segmentation label was used. The model was trained alternately on these two datasets with different types of teaching signals. We also proposed a variance estimation method for the final prediction. Our algorithm ranked the 4th on the test set in this competition.

##### Abstract (translated by Google)
在磁共振成像（MRI）图像中分割人体左心室（LV）并计算其体积对于诊断心脏疾病是重要的。 2016年，Kaggle组织了一场比赛来评估MRI图像的左室容量。数据集由大量病例组成，但仅提供收缩和舒张量作为标签。我们设计了一个基于神经网络的系统来解决这个问题。它开始于与神经网络分类器结合的检测器，用于检测包含LV室的感兴趣区域（ROI）。然后用一个名为hypercolumns全卷积网络的深层神经网络对ROI中的LV进行分割。 2D分割结果被整合到不同的图像中以估计音量。使用地面真实体积标签，此模型是端对端培训。为了改善结果，使用仅具有分割标签的附加数据集。在这两个数据集上交替使用不同类型的示教信号对模型进行训练。我们还提出了最终预测的方差估计方法。我们的算法在本次比赛中排名第四。

##### URL
[https://arxiv.org/abs/1702.03833](https://arxiv.org/abs/1702.03833)

##### PDF
[https://arxiv.org/pdf/1702.03833](https://arxiv.org/pdf/1702.03833)

