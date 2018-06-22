---
layout: post
title: "Finding Original Image Of A Sub Image Using CNNs"
date: 2018-06-21 06:24:08
categories: arXiv_CV
tags: arXiv_CV Object_Detection Image_Classification Classification Detection
author: Raja Asim
mathjax: true
---

* content
{:toc}

##### Abstract
Convolututional Neural Networks have achieved state of the art in image classification, object detection and other image related tasks. In this paper I present another use of CNNs i.e. if given a set of images and then giving a single test image the network identifies that the test image is part of which image from the images given before. This is a task somehow similar to measuring image similarity and can be done using a simple CNN. Doing this task manually by looping can be quite a time consuming problem and won't be a generalizable solution. The task is quite similar to doing object detection but for that lots training data should be given or in the case of sliding window it takes lot of time and my algorithm can work with much fewer examples, is totally unsupervised and works much efficiently. Also, I explain that how unsupervised algorithm like K-Means or supervised algorithm like K-NN are not good enough to perform this task. The basic idea is that image encodings are collected for each image from a CNN, when a test image comes it is replaced by a part of original image, the encoding is generated using the same network, the frobenius norm is calculated and if it comes under a tolerance level then the test image is said to be the part of the original image.

##### Abstract (translated by Google)
卷积神经网络已经实现了图像分类，目标检测和其他图像相关任务的最新技术。在本文中，我介绍了CNN的另一种用法，即如果给定一组图像，然后给出单个测试图像，则网络识别测试图像是来自之前给出的图像的那部分图像。这是一项类似于测量图像相似性的任务，可以使用简单的CNN完成。通过循环手动执行此任务可能是一个相当耗时的问题，并不是一个通用的解决方案。这个任务与做对象检测非常相似，但是应该给出大量的训练数据，或者在滑动窗口的情况下需要很多时间，我的算法可以用更少的例子工作，完全没有监督并且工作效率很高。另外，我解释了像K-Means这样的无监督算法或像K-NN这样的监督算法如何不足以完成这项任务。其基本思想是对于来自CNN的每个图像收集图像编码，当测试图像出现时它被替换为原始图像的一部分，使用相同网络生成编码，计算frobenius范数并且如果它来到公差水平，则测试图像被认为是原始图像的一部分。

##### URL
[http://arxiv.org/abs/1806.08078](http://arxiv.org/abs/1806.08078)

##### PDF
[http://arxiv.org/pdf/1806.08078](http://arxiv.org/pdf/1806.08078)

