---
layout: post
title: "TumorNet: Lung Nodule Characterization Using Multi-View Convolutional Neural Network with Gaussian Process"
date: 2017-03-02 07:26:37
categories: arXiv_CV
tags: arXiv_CV CNN
author: Sarfaraz Hussein, Robert Gillies, Kunlin Cao, Qi Song, Ulas Bagci
mathjax: true
---

* content
{:toc}

##### Abstract
Characterization of lung nodules as benign or malignant is one of the most important tasks in lung cancer diagnosis, staging and treatment planning. While the variation in the appearance of the nodules remains large, there is a need for a fast and robust computer aided system. In this work, we propose an end-to-end trainable multi-view deep Convolutional Neural Network (CNN) for nodule characterization. First, we use median intensity projection to obtain a 2D patch corresponding to each dimension. The three images are then concatenated to form a tensor, where the images serve as different channels of the input image. In order to increase the number of training samples, we perform data augmentation by scaling, rotating and adding noise to the input image. The trained network is used to extract features from the input image followed by a Gaussian Process (GP) regression to obtain the malignancy score. We also empirically establish the significance of different high level nodule attributes such as calcification, sphericity and others for malignancy determination. These attributes are found to be complementary to the deep multi-view CNN features and a significant improvement over other methods is obtained.

##### Abstract (translated by Google)
肺结节表现为良性或恶性是肺癌诊断，分期和治疗计划中最重要的任务之一。尽管结节外观的变化仍然很大，但仍需要一个快速而健壮的计算机辅助系统。在这项工作中，我们提出了一个端到端的可训练的多视点深度卷积神经网络（CNN）结核特征。首先，我们使用中值强度投影来获得与每个维度相对应的2D贴片。然后将三个图像连接起来形成张量，其中图像用作输入图像的不同通道。为了增加训练样本的数量，我们通过缩放，旋转和添加噪声到输入图像来执行数据增强。训练好的网络用于从输入图像中提取特征，然后进行高斯过程（GP）回归以获得恶性评分。我们还通过实验确定了不同的高级结节属性，如钙化，球形等，对恶性肿瘤的判断具有重要意义。发现这些属性是对深度多视图CNN特征的补充，并且获得了相对于其他方法的显着改进。

##### URL
[https://arxiv.org/abs/1703.00645](https://arxiv.org/abs/1703.00645)

##### PDF
[https://arxiv.org/pdf/1703.00645](https://arxiv.org/pdf/1703.00645)

