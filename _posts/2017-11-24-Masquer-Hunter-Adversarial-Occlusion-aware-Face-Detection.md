---
layout: post
title: "Masquer Hunter: Adversarial Occlusion-aware Face Detection"
date: 2017-11-24 13:40:55
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection Segmentation Face Detection Face_Detection
author: Yujia Chen, Lingxiao Song, Ran He
mathjax: true
---

* content
{:toc}

##### Abstract
Occluded face detection is a challenging detection task due to the large appearance variations incurred by various real-world occlusions. This paper introduces an Adversarial Occlusion-aware Face Detector (AOFD) by simultaneously detecting occluded faces and segmenting occluded areas. Specifically, we employ an adversarial training strategy to generate occlusion-like face features that are difficult for a face detector to recognize. Occlusion mask is predicted simultaneously while detecting occluded faces and the occluded area is utilized as an auxiliary instead of being regarded as a hindrance. Moreover, the supervisory signals from the segmentation branch will reversely affect the features, aiding in detecting heavily-occluded faces accordingly. Consequently, AOFD is able to find the faces with few exposed facial landmarks with very high confidences and keeps high detection accuracy even for masked faces. Extensive experiments demonstrate that AOFD not only significantly outperforms state-of-the-art methods on the MAFA occluded face detection dataset, but also achieves competitive detection accuracy on benchmark dataset for general face detection such as FDDB.

##### Abstract (translated by Google)
由于各种现实世界的遮挡引起的大的外观变化，遮挡的人脸检测是一项具有挑战性的检测任务。本文通过同时检测遮挡面和分割遮挡区，引入了对抗性遮挡感知的人脸检测器（AOFD）。具体而言，我们采用对抗训练策略来产生面部检测器难以识别的遮挡式脸部特征。在检测遮挡面的同时预测遮挡遮罩，并且将遮挡区域用作辅助而不是被视为阻碍。此外，来自分割分支的监控信号将逆向地影响特征，从而协助检测严重遮挡的面部。因此，AOFD能够以非常高的置信度找到几乎没有暴露的面部标志的面部，并且即使对于蒙面的面部也保持高的检测精度。大量的实验表明，AOFD不仅在MAFA遮挡人脸检测数据集上显着优于现有技术，而且在FDDB等一般人脸检测的基准数据集上也具有较高的检测精度。

##### URL
[https://arxiv.org/abs/1709.05188](https://arxiv.org/abs/1709.05188)

##### PDF
[https://arxiv.org/pdf/1709.05188](https://arxiv.org/pdf/1709.05188)

