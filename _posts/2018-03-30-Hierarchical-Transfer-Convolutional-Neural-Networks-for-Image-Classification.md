---
layout: post
title: "Hierarchical Transfer Convolutional Neural Networks for Image Classification"
date: 2018-03-30 18:19:32
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification
author: Xishuang Dong, Hsiang-Huang Wu, Yuzhong Yan, Lijun Qian
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we address the issue of how to enhance the generalization performance of convolutional neural networks (CNN) in the early learning stage for image classification. This is motivated by real-time applications that require the generalization performance of CNN to be satisfactory within limited training time. In order to achieve this, a novel hierarchical transfer CNN framework is proposed. It consists of a group of shallow CNNs and a cloud CNN, where the shallow CNNs are trained firstly and then the first layers of the trained shallow CNNs are used to initialize the first layer of the cloud CNN. This method will boost the generalization performance of the cloud CNN significantly, especially during the early stage of training. Experiments using CIFAR-10 and ImageNet datasets are performed to examine the proposed method. Results demonstrate the improvement of testing accuracy is 12% on average and as much as 20% for the CIFAR-10 case while 5% testing accuracy improvement for the ImageNet case during the early stage of learning. It is also shown that universal improvements of testing accuracy are obtained across different settings of dropout and number of shallow CNNs.

##### Abstract (translated by Google)
在本文中，我们讨论如何在图像分类的早期学习阶段提高卷积神经网络（CNN）的泛化性能。这受实时应用程序的驱使，要求CNN的泛化性能在有限的培训时间内达到令人满意的程度。为了实现这一点，提出了一种新型的等级转移CNN框架。它由一组浅CNN和一个云CNN组成，首先训练浅CNN，然后使用训练的浅CNN的第一层初始化云CNN的第一层。这种方法将显着提高云CNN的泛化性能，特别是在培训的早期阶段。使用CIFAR-10和ImageNet数据集进行实验来检查所提出的方法。结果表明，在学习初期，测试准确性平均提高12％，CIFAR-10病例提高20％，而ImageNet病例测试准确性提高5％。这也表明，在不同的退出设置和浅CNN数量下，测试精度的普遍提高得到了实现。

##### URL
[http://arxiv.org/abs/1804.00021](http://arxiv.org/abs/1804.00021)

##### PDF
[http://arxiv.org/pdf/1804.00021](http://arxiv.org/pdf/1804.00021)

