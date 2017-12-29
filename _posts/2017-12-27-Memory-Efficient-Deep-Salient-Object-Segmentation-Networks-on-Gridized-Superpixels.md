---
layout: post
title: "Memory-Efficient Deep Salient Object Segmentation Networks on Gridized Superpixels"
date: 2017-12-27 12:20:13
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection Segmentation CNN Semantic_Segmentation Deep_Learning Detection
author: Caglar Aytekin, Xingyang Ni, Francesco Cricri, Lixin Fan, Emre Aksu
mathjax: true
---

* content
{:toc}

##### Abstract
Computer vision algorithms with pixel-wise labeling tasks, such as semantic segmentation and salient object detection, have gone through a significant accuracy increase with the incorporation of deep learning. Deep segmentation methods slightly modify and fine-tune pre-trained networks that have hundreds of millions of parameters. In this work, we question the need to have such memory demanding networks for the specific task of salient object segmentation. To this end, we propose a way to learn a memory-efficient network from scratch by training it only on salient object detection datasets. Our method encodes images to gridized superpixels that preserve both the object boundaries and the connectivity rules of regular pixels. This representation allows us to use convolutional neural networks that operate on regular grids. By using these encoded images, we train a memory-efficient network using only 0.048\% of the number of parameters that other deep salient object detection networks have. Our method shows comparable accuracy with the state-of-the-art deep salient object detection methods and provides a faster and a much more memory-efficient alternative to them. Due to its easy deployment, such a network is preferable for applications in memory limited devices such as mobile phones and IoT devices.

##### Abstract (translated by Google)
计算机视觉算法与像素标签任务，如语义分割和显着物体检测，已经通过深入学习的显着精度提高。深度分割方法稍微修改和微调具有数亿个参数的预先训练的网络。在这项工作中，我们质疑需要有这样的内存要求网络的显着对象分割的具体任务。为此，我们提出了一种通过仅在显着物体检测数据集上进行训练来从头开始学习高效存储网络的方法。我们的方法将图像编码为网格化超像素，保留了对象边界和常规像素的连通性规则。这种表示允许我们使用在规则网格上运行的卷积神经网络。通过使用这些编码图像，我们只使用其他深度显着物体检测网络所具有的参数数量的0.048％来训练一个高效的网络。我们的方法与现有技术的深度显着物体检测方法显示出相当的准确性，并为他们提供了更快，更高效的内存选择。由于易于部署，这种网络对于手机和物联网设备等限制内存的设备的应用来说是优选的。

##### URL
[http://arxiv.org/abs/1712.09558](http://arxiv.org/abs/1712.09558)

##### PDF
[http://arxiv.org/pdf/1712.09558](http://arxiv.org/pdf/1712.09558)

