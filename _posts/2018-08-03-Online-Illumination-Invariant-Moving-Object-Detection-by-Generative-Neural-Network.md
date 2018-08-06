---
layout: post
title: "Online Illumination Invariant Moving Object Detection by Generative Neural Network"
date: 2018-08-03 02:11:32
categories: arXiv_CV
tags: arXiv_CV Image_Caption Object_Detection Optimization Detection Gradient_Descent
author: Fateme Bahri, Moein Shakeri, Nilanjan Ray
mathjax: true
---

* content
{:toc}

##### Abstract
Moving object detection (MOD) is a significant problem in computer vision that has many real world applications. Different categories of methods have been proposed to solve MOD. One of the challenges is to separate moving objects from illumination changes and shadows that are present in most real world videos. State-of-the-art methods that can handle illumination changes and shadows work in a batch mode; thus, these methods are not suitable for long video sequences or real-time applications. In this paper, we propose an extension of a state-of-the-art batch MOD method (ILISD) to an online/incremental MOD using unsupervised and generative neural networks, which use illumination invariant image representations. For each image in a sequence, we use a low-dimensional representation of a background image by a neural network and then based on the illumination invariant representation, decompose the foreground image into: illumination change and moving objects. Optimization is performed by stochastic gradient descent in an end-to-end and unsupervised fashion. Our algorithm can work in both batch and online modes. In the batch mode, like other batch methods, optimizer uses all the images. In online mode, images can be incrementally fed into the optimizer. Based on our experimental evaluation on benchmark image sequences, both the online and the batch modes of our algorithm achieve state-of-the-art accuracy on most data sets.

##### Abstract (translated by Google)
移动物体检测（MOD）是计算机视觉中的重要问题，其具有许多现实世界的应用。已经提出了不同类别的方法来解决MOD。其中一个挑战是将移动物体与大多数真实世界视频中存在的照明变化和阴影分开。可以处理照明变化和阴影的最先进方法以批处理模式工作;因此，这些方法不适用于长视频序列或实时应用。在本文中，我们提出使用无监督和生成神经网络将最先进的批量MOD方法（ILISD）扩展到在线/增量MOD，其使用光照不变图像表示。对于序列中的每个图像，我们通过神经网络使用背景图像的低维表示，然后基于照明不变表示，将前景图像分解为：照明变化和移动对象。通过端对端和无监督方式的随机梯度下降来执行优化。我们的算法可以在批处理和在线模式下工作。在批处理模式下，与其他批处理方法一样，优化程序使用所有图像。在在线模式下，图像可以逐步输入优化器。基于我们对基准图像序列的实验评估，我们的算法的在线和批处理模式在大多数数据集上都达到了最先进的精度。

##### URL
[http://arxiv.org/abs/1808.01066](http://arxiv.org/abs/1808.01066)

##### PDF
[http://arxiv.org/pdf/1808.01066](http://arxiv.org/pdf/1808.01066)

