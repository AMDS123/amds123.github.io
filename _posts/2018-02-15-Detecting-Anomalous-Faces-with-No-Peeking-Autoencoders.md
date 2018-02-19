---
layout: post
title: "Detecting Anomalous Faces with 'No Peeking' Autoencoders"
date: 2018-02-15 23:35:37
categories: arXiv_CV
tags: arXiv_CV Face Detection
author: Anand Bhattad, Jason Rock, David Forsyth
mathjax: true
---

* content
{:toc}

##### Abstract
Detecting anomalous faces has important applications. For example, a system might tell when a train driver is incapacitated by a medical event, and assist in adopting a safe recovery strategy. These applications are demanding, because they require accurate detection of rare anomalies that may be seen only at runtime. Such a setting causes supervised methods to perform poorly. We describe a method for detecting an anomalous face image that meets these requirements. We construct a feature vector that reliably has large entries for anomalous images, then use various simple unsupervised methods to score the image based on the feature. Obvious constructions (autoencoder codes; autoencoder residuals) are defeated by a 'peeking' behavior in autoencoders. Our feature construction removes rectangular patches from the image, predicts the likely content of the patch conditioned on the rest of the image using a specially trained autoencoder, then compares the result to the image. High scores suggest that the patch was difficult for an autoencoder to predict, and so is likely anomalous. We demonstrate that our method can identify real anomalous face images in pools of typical images, taken from celeb-A, that is much larger than usual in state-of-the-art experiments. A control experiment based on our method with another set of normal celebrity images - a 'typical set', but nonceleb-A are not identified as anomalous; confirms this is not due to special properties of celeb-A.

##### Abstract (translated by Google)
检测异常面部有重要的应用。例如，一个系统可能会告诉火车司机何时因医疗事故而丧失工作能力，并协助采取安全的恢复策略。这些应用程序要求很高，因为它们需要精确检测仅在运行时才能看到的罕见异常情况。这样的设置会导致监督方法执行得不好。我们描述了一种检测符合这些要求的异常人脸图像的方法。我们构造了一个特征向量，可靠地拥有较大的异常图像条目，然后使用各种简单的无监督方法根据特征对图像进行评分。明显的构造（自动编码器代码;自动编码器残差）在自动编码器中被“窥视”行为击败。我们的特征构造从图像中移除矩形色块，使用经过特殊训练的自动编码器预测补丁可能的内容，然后将结果与图像进行比较。高分表明该补丁对于自动编码器难以预测，因此可能是异常的。我们证明，我们的方法可以识别典型图像池中真正的异常人脸图像，取自celeb-A，这比最常用的实验要大得多。一个控制实验基于我们的方法与另一套正常的名人图像 - 一个“典型集合”，但nonceleb-A没有被识别为异常;证实这不是由于celeb-A的特殊属性造成的。

##### URL
[https://arxiv.org/abs/1802.05798](https://arxiv.org/abs/1802.05798)

##### PDF
[https://arxiv.org/pdf/1802.05798](https://arxiv.org/pdf/1802.05798)

