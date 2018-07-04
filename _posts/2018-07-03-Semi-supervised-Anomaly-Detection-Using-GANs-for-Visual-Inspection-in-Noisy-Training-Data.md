---
layout: post
title: "Semi-supervised Anomaly Detection Using GANs for Visual Inspection in Noisy Training Data"
date: 2018-07-03 13:03:11
categories: arXiv_CV
tags: arXiv_CV Attention GAN Detection
author: Masanari Kimura, Takashi Yanagihara
mathjax: true
---

* content
{:toc}

##### Abstract
The detection and the quantification of anomalies in image data are critical tasks in industrial scenes such as detecting micro scratches on product. In recent years, due to the difficulty of defining anomalies and the limit of correcting their labels, research on unsupervised anomaly detection using generative models has attracted attention. Generally, in those studies, only normal images are used for training to model the distribution of normal images. The model measures the anomalies in the target images by reproducing the most similar images and scoring image patches indicating their fit to the learned distribution. This approach is based on a strong presumption; the trained model should not be able to generate abnormal images. However, in reality, the model can generate abnormal images mainly due to noisy normal data which include small abnormal pixels, and such noise severely affects the accuracy of the model. Therefore, we propose a novel semi-supervised method to distort the distribution of the model with existing abnormal images. The proposed method detects pixel-level micro anomalies with a high accuracy from 1024x1024 high resolution images which are actually used in an industrial scene. In this paper, we share experimental results on open datasets, due to the confidentiality of the data.

##### Abstract (translated by Google)
图像数据中异常的检测和量化是工业场景中的关键任务，例如检测产品上的微划痕。近年来，由于难以定义异常和校正标​​签的限制，使用生成模型进行无监督异常检测的研究引起了人们的关注。通常，在那些研究中，仅将正常图像用于训练以模拟正常图像的分布。该模型通过再现最相似的图像并对图像块进行评分来测量目标图像中的异常，从而指示它们与学习的分布的拟合。这种方法基于强有力的推定;受过训练的模型不应该能够生成异常图像。然而，实际上，该模型可能主要由于包括小异常像素的噪声正常数据而产生异常图像，并且这种噪声严重影响模型的准确性。因此，我们提出了一种新的半监督方法来扭曲模型的分布与现有的异常图像。所提出的方法从1024x1024高分辨率图像中高精度地检测像素级微异常，这些图像实际上在工业场景中使用。在本文中，由于数据的机密性，我们在开放数据集上分享实验结果。

##### URL
[https://arxiv.org/abs/1807.01136](https://arxiv.org/abs/1807.01136)

##### PDF
[https://arxiv.org/pdf/1807.01136](https://arxiv.org/pdf/1807.01136)

