---
layout: post
title: "Cross-dataset Person Re-Identification Using Similarity Preserved Generative Adversarial Networks"
date: 2018-06-11 03:40:06
categories: arXiv_CV
tags: arXiv_CV Re-identification Adversarial GAN Person_Re-identification CNN
author: Jianming Lv, Xintong Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Person re-identification (Re-ID) aims to match the image frames which contain the same person in the surveillance videos. Most of the Re-ID algorithms conduct supervised training in some small labeled datasets, so directly deploying these trained models to the real-world large camera networks may lead to a poor performance due to underfitting. The significant difference between the source training dataset and the target testing dataset makes it challenging to incrementally optimize the model. To address this challenge, we propose a novel solution by transforming the unlabeled images in the target domain to fit the original classifier by using our proposed similarity preserved generative adversarial networks model, SimPGAN. Specifically, SimPGAN adopts the generative adversarial networks with the cycle consistency constraint to transform the unlabeled images in the target domain to the style of the source domain. Meanwhile, SimPGAN uses the similarity consistency loss, which is measured by a siamese deep convolutional neural network, to preserve the similarity of the transformed images of the same person. Comprehensive experiments based on multiple real surveillance datasets are conducted, and the results show that our algorithm is better than the state-of-the-art cross-dataset unsupervised person Re-ID algorithms.

##### Abstract (translated by Google)
个人重新识别（Re-ID）旨在匹配监控视频中包含同一个人的图像帧。大多数Re-ID算法在一些小的标记数据集中进行有监督的训练，因此直接将这些训练好的模型部署到现实世界的大型摄像机网络可能会导致由于不足的不良性能。源训练数据集与目标测试数据集之间的显着差异使增量优化模型变得具有挑战性。为了解决这个难题，我们提出了一种新的解决方案，通过使用我们提出的相似性保存的生成敌对网络模型SimPGAN，将目标域中的未标记图像变换为适合原始分类器。具体而言，SimPGAN采用具有周期一致性约束的生成对抗网络将目标域中的未标记图像转换为源域的风格。同时，SimPGAN使用由连体深度卷积神经网络测量的相似性一致性损失来保持同一个人的变换图像的相似性。基于多个实际监测数据集进行综合实验，结果表明，该算法优于最先进的交叉数据集无监督人Re-ID算法。

##### URL
[http://arxiv.org/abs/1806.04533](http://arxiv.org/abs/1806.04533)

##### PDF
[http://arxiv.org/pdf/1806.04533](http://arxiv.org/pdf/1806.04533)

