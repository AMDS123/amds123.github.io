---
layout: post
title: "Fully Convolutional Architectures for Multi-Class Segmentation in Chest Radiographs"
date: 2018-02-13 16:12:40
categories: arXiv_CV
tags: arXiv_CV Regularization Segmentation GAN CNN Image_Classification Classification Recognition
author: Alexey A. Novikov, Dimitrios Lenis, David Major, Jiri Hlad&#x16f;vka, Maria Wimmer, Katja B&#xfc;hler
mathjax: true
---

* content
{:toc}

##### Abstract
The success of deep convolutional neural networks on image classification and recognition tasks has led to new applications in very diversified contexts, including the field of medical imaging. In this paper we investigate and propose neural network architectures for automated multi-class segmentation of anatomical organs in chest radiographs, namely for lungs, clavicles and heart. We address several open challenges including model overfitting, reducing number of parameters and handling of severely imbalanced data in CXR by fusing recent concepts in convolutional networks and adapting them to the segmentation problem task in CXR. We demonstrate that our architecture combining delayed subsampling, exponential linear units, highly restrictive regularization and a large number of high resolution low level abstract features outperforms state-of-the-art methods on all considered organs, as well as the human observer on lungs and heart. The models use a multi-class configuration with three target classes and are trained and tested on the publicly available JSRT database, consisting of 247 X-ray images the ground-truth masks for which are available in the SCR database. Our best performing model, trained with the loss function based on the Dice coefficient, reached mean Jaccard overlap scores of 95.0\% for lungs, 86.8\% for clavicles and 88.2\% for heart. This architecture outperformed the human observer results for lungs and heart.

##### Abstract (translated by Google)
深卷积神经网络在图像分类和识别任务上的成功已经导致了在包括医学成像领域在内的多元化背景下的新应用。在本文中，我们调查并提出了神经网络架构，用于胸部X光片中解剖器官的自动化多级分割，即肺，锁骨和心脏。我们通过融合卷积网络中最近的概念并将它们适配到CXR中的分割问题任务，解决了CXR中包括模型过拟合，减少参数数量和处理严重不平衡数据的几个开放挑战。我们证明，我们的体系结构结合了延迟子采样，指数线性单位，高度限制性正则化和大量高分辨率低水平抽象特征，在所有考虑的器官以及人类肺部观察者方面均优于最先进的方法，心。这些模型使用三类目标的多类配置，并在公开可用的JSRT数据库上进行训练和测试，该数据库由247张X射线图像组成，这些图像是SCR数据库中可用的地面实况蒙版。我们的表现最好的模型，基于Dice系数的损失函数进行训练，得到的平均Jaccard重叠分数为肺的95.0％，锁骨的86.8％和心脏的88.2％。这种架构胜过了人类对肺和心脏的观察结果。

##### URL
[http://arxiv.org/abs/1701.08816](http://arxiv.org/abs/1701.08816)

##### PDF
[http://arxiv.org/pdf/1701.08816](http://arxiv.org/pdf/1701.08816)

