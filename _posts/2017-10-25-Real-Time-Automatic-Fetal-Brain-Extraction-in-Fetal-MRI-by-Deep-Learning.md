---
layout: post
title: "Real-Time Automatic Fetal Brain Extraction in Fetal MRI by Deep Learning"
date: 2017-10-25 16:54:44
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN Tracking CNN Deep_Learning Detection
author: Seyed Sadegh Mohseni Salehi, Seyed Raein Hashemi, Clemente Velasco-Annis, Abdelhakim Ouaalam, Judy A. Estroff, Deniz Erdogmus, Simon K. Warfield, Ali Gholipour
mathjax: true
---

* content
{:toc}

##### Abstract
Brain segmentation is a fundamental first step in neuroimage analysis. In the case of fetal MRI, it is particularly challenging and important due to the arbitrary orientation of the fetus, organs that surround the fetal head, and intermittent fetal motion. Several promising methods have been proposed but are limited in their performance in challenging cases and in real-time segmentation. We aimed to develop a fully automatic segmentation method that independently segments sections of the fetal brain in 2D fetal MRI slices in real-time. To this end, we developed and evaluated a deep fully convolutional neural network based on 2D U-net and autocontext, and compared it to two alternative fast methods based on 1) a voxelwise fully convolutional network and 2) a method based on SIFT features, random forest and conditional random field. We trained the networks with manual brain masks on 250 stacks of training images, and tested on 17 stacks of normal fetal brain images as well as 18 stacks of extremely challenging cases based on extreme motion, noise, and severely abnormal brain shape. Experimental results show that our U-net approach outperformed the other methods and achieved average Dice metrics of 96.52% and 78.83% in the normal and challenging test sets, respectively. With an unprecedented performance and a test run time of about 1 second, our network can be used to segment the fetal brain in real-time while fetal MRI slices are being acquired. This can enable real-time motion tracking, motion detection, and 3D reconstruction of fetal brain MRI.

##### Abstract (translated by Google)
大脑分割是神经图像分析的基本第一步。就胎儿MRI而言，由于胎儿的任意取向，胎头周围的器官和间歇的胎儿运动，这尤其具有挑战性和重要性。已经提出了几种有前途的方法，但在具有挑战性的情况下以及在实时分割中的性能受到限制。我们的目标是开发一种全自动分割方法，能够实时地在2D胎儿的MRI切片中独立分割胎儿脑部分。为此，我们开发并评估了一个基于二维U-net和自动同步的深度全卷积神经网络，并将其与两种基于1）voxelwise全卷积网络和2）基于SIFT特征的快速方法进行了比较，随机森林和条件随机场。我们用250张训练图像的手动大脑面罩训练网络，并在17个正常胎儿脑图像堆栈上进行测试，以及基于极端运动，噪声和严重异常脑形状的18堆极具挑战性的病例。实验结果表明，我们的U-net方法优于其他方法，在正常和具有挑战性的测试集中分别达到96.52％和78.83％的平均Dice度量。凭借前所未有的性能和大约1秒的测试运行时间，我们的网络可用于实时分割胎儿脑部，同时获取胎儿MRI片段。这可以实现胎儿大脑MRI的实时运动追踪，运动检测和三维重建。

##### URL
[https://arxiv.org/abs/1710.09338](https://arxiv.org/abs/1710.09338)

##### PDF
[https://arxiv.org/pdf/1710.09338](https://arxiv.org/pdf/1710.09338)

