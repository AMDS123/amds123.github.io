---
layout: post
title: "Image Forensics: Detecting duplication of scientific images with manipulation-invariant image similarity"
date: 2018-02-19 04:41:24
categories: arXiv_CV
tags: arXiv_CV Review CNN
author: M. Cicconet, H. Elliott, D.L. Richmond, D. Wainstock, M. Walsh
mathjax: true
---

* content
{:toc}

##### Abstract
Manipulation and re-use of images in scientific publications is a concerning problem that currently lacks a scalable solution. Current tools for detecting image duplication are mostly manual or semi-automated, despite the availability of an overwhelming target dataset for a learning-based approach. This paper addresses the problem of determining if, given two images, one is a manipulated version of the other by means of copy, rotation, translation, scale, perspective transform, histogram adjustment, or partial erasing. We propose a data-driven solution based on a 3-branch Siamese Convolutional Neural Network. The ConvNet model is trained to map images into a 128-dimensional space, where the Euclidean distance between duplicate images is smaller than or equal to 1, and the distance between unique images is greater than 1. Our results suggest that such an approach has the potential to improve surveillance of the published and in-peer-review literature for image manipulation.

##### Abstract (translated by Google)
在科学出版物中操作和重复使用图像是一个有关的问题，目前缺乏可扩展的解决方案。目前用于检测图像复制的工具大部分是手动或半自动的，尽管可以使用基于学习的方法的压倒性目标数据集。本文讨论了如何确定给定两幅图像是否通过复制，旋转，平移，缩放，透视变换，直方图调整或局部擦除来操作另一幅图像的问题。我们提出了基于3分支连体卷积神经网络的数据驱动解决方案。 ConvNet模型被训练成将图像映射到128维空间，其中重复图像之间的欧几里得距离小于或等于1，并且独特图像之间的距离大于1.我们的结果表明这样的方法具有有可能改进对图像处理的已发表和同行评审文献的监督。

##### URL
[http://arxiv.org/abs/1802.06515](http://arxiv.org/abs/1802.06515)

##### PDF
[http://arxiv.org/pdf/1802.06515](http://arxiv.org/pdf/1802.06515)

