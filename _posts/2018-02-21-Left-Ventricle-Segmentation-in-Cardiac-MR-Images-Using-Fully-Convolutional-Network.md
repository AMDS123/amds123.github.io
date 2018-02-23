---
layout: post
title: "Left Ventricle Segmentation in Cardiac MR Images Using Fully Convolutional Network"
date: 2018-02-21 20:01:35
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN CNN
author: Mina Nasr-Esfahani, Majid Mohrekesh, Mojtaba Akbari, S.M.Reza Soroushmehr, Ebrahim Nasr-Esfahani, Nader Karimi, Shadrokh Samavi, Kayvan Najarian
mathjax: true
---

* content
{:toc}

##### Abstract
Medical image analysis, especially segmenting a specific organ, has an important role in developing clinical decision support systems. In cardiac magnetic resonance (MR) imaging, segmenting the left and right ventricles helps physicians diagnose different heart abnormalities. There are challenges for this task, including the intensity and shape similarity between left ventricle and other organs, inaccurate boundaries and presence of noise in most of the images. In this paper we propose an automated method for segmenting the left ventricle in cardiac MR images. We first automatically extract the region of interest, and then employ it as an input of a fully convolutional network. We train the network accurately despite the small number of left ventricle pixels in comparison with the whole image. Thresholding on the output map of the fully convolutional network and selection of regions based on their roundness are performed in our proposed post-processing phase. The Dice score of our method reaches 87.24% by applying this algorithm on the York dataset of heart images.

##### Abstract (translated by Google)
医学图像分析，特别是分割特定器官，在开发临床决策支持系统方面发挥着重要作用。在心脏磁共振（MR）成像中，分割左心室和右心室可帮助医生诊断不同的心脏异常。这项任务存在挑战，包括左心室和其他器官之间的强度和形状相似性，不准确的边界以及大多数图像中的噪声。在本文中，我们提出了一种在心脏MR图像中分割左心室的自动化方法。我们首先自动提取感兴趣区域，然后将其用作完全卷积网络的输入。尽管与整个图像相比，尽管左心室像素的数量很少，我们仍然精确地训练网络。在我们提出的后处理阶段，完全卷积网络的输出图上的阈值选择和基于它们圆度的区域选择被执行。通过在心脏图像的York数据集上应用该算法，我们的方法的Dice分数达到87.24％。

##### URL
[http://arxiv.org/abs/1802.07778](http://arxiv.org/abs/1802.07778)

##### PDF
[http://arxiv.org/pdf/1802.07778](http://arxiv.org/pdf/1802.07778)

