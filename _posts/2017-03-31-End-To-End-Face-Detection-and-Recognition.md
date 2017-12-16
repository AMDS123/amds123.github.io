---
layout: post
title: "End-To-End Face Detection and Recognition"
date: 2017-03-31 09:48:32
categories: arXiv_CV
tags: arXiv_CV Face CNN Detection Face_Detection Recognition Face_Recognition
author: Liying Chi, Hongxin Zhang, Mingxiu Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Plenty of face detection and recognition methods have been proposed and got delightful results in decades. Common face recognition pipeline consists of: 1) face detection, 2) face alignment, 3) feature extraction, 4) similarity calculation, which are separated and independent from each other. The separated face analyzing stages lead the model redundant calculation and are hard for end-to-end training. In this paper, we proposed a novel end-to-end trainable convolutional network framework for face detection and recognition, in which a geometric transformation matrix was directly learned to align the faces, instead of predicting the facial landmarks. In training stage, our single CNN model is supervised only by face bounding boxes and personal identities, which are publicly available from WIDER FACE \cite{Yang2016} dataset and CASIA-WebFace \cite{Yi2014} dataset. Tested on Face Detection Dataset and Benchmark (FDDB) \cite{Jain2010} dataset and Labeled Face in the Wild (LFW) \cite{Huang2007} dataset, we have achieved 89.24\% recall for face detection task and 98.63\% verification accuracy for face recognition task simultaneously, which are comparable to state-of-the-art results.

##### Abstract (translated by Google)
数十年来，人们提出了大量的人脸检测和识别方法，取得了令人满意的成果。常见的人脸识别流水线包括：1）人脸检测，2）人脸对齐，3）特征提取，4）相似性计算，它们是相互分离和相互独立的。分离的人脸分析阶段导致模型冗余计算，难以进行端到端的训练。在本文中，我们提出了一种面向人脸检测和识别的端到端可训练卷积网络框架，其中直接学习几何变换矩阵来对齐人脸，而不是预测面部标志。在训练阶段，我们单一的CNN模型只能通过面部边界框和个人身份进行监控，这些边界框和个人身份可以从WIDER FACE \ cite {Yang2016}数据集和CASIA-WebFace \ cite {Yi2014}数据集公开获得。对人脸检测数据集和基准（FDDB）\ cite {Jain2010}数据集和Labeled Face in the Wild（LFW）\ cite {Huang2007}数据集进行测试，得到了面部检测任务的回忆率为89.24％，验证精度为98.63％面部识别任务同时进行，这与最先进的结果相媲美。

##### URL
[https://arxiv.org/abs/1703.10818](https://arxiv.org/abs/1703.10818)

##### PDF
[https://arxiv.org/pdf/1703.10818](https://arxiv.org/pdf/1703.10818)

