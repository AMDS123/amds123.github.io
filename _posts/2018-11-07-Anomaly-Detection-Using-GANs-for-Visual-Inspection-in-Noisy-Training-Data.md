---
layout: post
title: "Anomaly Detection Using GANs for Visual Inspection in Noisy Training Data"
date: 2018-11-07 15:44:07
categories: arXiv_CV
tags: arXiv_CV Attention GAN Detection
author: Masanari Kimura, Takashi Yanagihara
mathjax: true
---

* content
{:toc}

##### Abstract
The detection and the quantification of anomalies in image data are critical tasks in industrial scenes such as detecting micro scratches on product. In recent years, due to the difficulty of defining anomalies and the limit of correcting their labels, research on unsupervised anomaly detection using generative models has attracted attention. Generally, in those studies, only normal images are used for training to model the distribution of normal images. The model measures the anomalies in the target images by reproducing the most similar images and scoring image patches indicating their fit to the learned distribution. This approach is based on a strong presumption; the trained model should not be able to generate abnormal images. However, in reality, the model can generate abnormal images mainly due to noisy normal data which include small abnormal pixels, and such noise severely affects the accuracy of the model. Therefore, we propose a novel anomaly detection method to distort the distribution of the model with existing abnormal images. The proposed method detects pixel-level micro anomalies with a high accuracy from 1024x1024 high resolution images which are actually used in an industrial scene. In this paper, we share experimental results on open datasets, due to the confidentiality of the data.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1807.01136](https://arxiv.org/abs/1807.01136)

##### PDF
[https://arxiv.org/pdf/1807.01136](https://arxiv.org/pdf/1807.01136)

