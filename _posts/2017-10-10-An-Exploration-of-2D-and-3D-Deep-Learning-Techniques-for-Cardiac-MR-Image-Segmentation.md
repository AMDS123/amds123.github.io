---
layout: post
title: "An Exploration of 2D and 3D Deep Learning Techniques for Cardiac MR Image Segmentation"
date: 2017-10-10 08:09:31
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Deep_Learning
author: Christian F. Baumgartner, Lisa M. Koch, Marc Pollefeys, Ender Konukoglu
mathjax: true
---

* content
{:toc}

##### Abstract
Accurate segmentation of the heart is an important step towards evaluating cardiac function. In this paper, we present a fully automated framework for segmentation of the left (LV) and right (RV) ventricular cavities and the myocardium (Myo) on short-axis cardiac MR images. We investigate various 2D and 3D convolutional neural network architectures for this task. We investigate the suitability of various state-of-the art 2D and 3D convolutional neural network architectures, as well as slight modifications thereof, for this task. Experiments were performed on the ACDC 2017 challenge training dataset comprising cardiac MR images of 100 patients, where manual reference segmentations were made available for end-diastolic (ED) and end-systolic (ES) frames. We find that processing the images in a slice-by-slice fashion using 2D networks is beneficial due to a relatively large slice thickness. However, the exact network architecture only plays a minor role. We report mean Dice coefficients of $0.950$ (LV), $0.893$ (RV), and $0.899$ (Myo), respectively with an average evaluation time of 1.1 seconds per volume on a modern GPU.

##### Abstract (translated by Google)
精确的心脏分割是评估心脏功能的重要步骤。在本文中，我们提出了一种全自动化的短轴心脏MR图像左室（LV）和右室（RV）心室腔和心肌（Myo）的分割框架。我们研究了这个任务的各种二维和三维卷积神经网络体系结构。我们研究了各种最先进的二维和三维卷积神经网络结构的适用性，以及对其进行的细微修改。在ACDC 2017挑战训练数据集上进行了实验，所述训练数据集包括100名患者的心脏MR图像，其中手动参考分段可用于舒张末期（ED）和收缩末期（ES）帧。我们发现，使用2D网络以逐片方式处理图像由于较大的切片厚度而是有利的。但是，确切的网络架构只起到次要的作用。我们报告的平均Dice系数分别为$ 0.950 $（LV），$ 0.893 $（RV）和$ 0.899 $（Myo），平均评估时间为1.1秒每个卷在现代GPU上。

##### URL
[https://arxiv.org/abs/1709.04496](https://arxiv.org/abs/1709.04496)

##### PDF
[https://arxiv.org/pdf/1709.04496](https://arxiv.org/pdf/1709.04496)

