---
layout: post
title: "Densely Connected Convolutional Networks and Signal Quality Analysis to Detect Atrial Fibrillation Using Short Single-Lead ECG Recordings"
date: 2017-10-10 18:58:45
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Jonathan Rubin, Saman Parvaneh, Asif Rahman, Bryan Conroy, Saeed Babaeizadeh
mathjax: true
---

* content
{:toc}

##### Abstract
The development of new technology such as wearables that record high-quality single channel ECG, provides an opportunity for ECG screening in a larger population, especially for atrial fibrillation screening. The main goal of this study is to develop an automatic classification algorithm for normal sinus rhythm (NSR), atrial fibrillation (AF), other rhythms (O), and noise from a single channel short ECG segment (9-60 seconds). For this purpose, signal quality index (SQI) along with dense convolutional neural networks was used. Two convolutional neural network (CNN) models (main model that accepts 15 seconds ECG and secondary model that processes 9 seconds shorter ECG) were trained using the training data set. If the recording is determined to be of low quality by SQI, it is immediately classified as noisy. Otherwise, it is transformed to a time-frequency representation and classified with the CNN as NSR, AF, O, or noise. At the final step, a feature-based post-processing algorithm classifies the rhythm as either NSR or O in case the CNN model's discrimination between the two is indeterminate. The best result achieved at the official phase of the PhysioNet/CinC challenge on the blind test set was 0.80 (F1 for NSR, AF, and O were 0.90, 0.80, and 0.70, respectively).

##### Abstract (translated by Google)
记录高质量单通道心电图的可穿戴设备等新技术的发展，为更多人群的心电图筛查提供了机会，特别是心房颤动筛查。本研究的主要目标是为正常窦性心律（NSR），心房颤动（AF），其他节律（O）和单通道短ECG段（9-60秒）的噪声开发自动分类算法。为此，使用信号质量指数（SQI）和密集卷积神经网络。使用训练数据集训练两个卷积神经网络（CNN）模型（接受15秒ECG的主模型和处理9秒短ECG的第二模型）。如果通过SQI确定记录质量低，则立即将其分类为噪音。否则，将其转换为时频表示，并将其与CNN分类为NSR，AF，O或噪声。在最后一步，基于特征的后处理算法将节奏分类为NSR或O，以防CNN模型在两者之间的区分是不确定的。在盲测试组的PhysioNet / CinC挑战官方阶段所取得的最好结果是0.80（NSR，AF和O的F1分别是0.90,0.80和0.70）。

##### URL
[https://arxiv.org/abs/1710.05817](https://arxiv.org/abs/1710.05817)

##### PDF
[https://arxiv.org/pdf/1710.05817](https://arxiv.org/pdf/1710.05817)

