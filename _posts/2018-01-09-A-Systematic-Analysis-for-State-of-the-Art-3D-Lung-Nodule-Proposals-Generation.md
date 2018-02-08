---
layout: post
title: "A Systematic Analysis for State-of-the-Art 3D Lung Nodule Proposals Generation"
date: 2018-01-09 01:13:33
categories: arXiv_CV
tags: arXiv_CV Attention CNN Detection
author: Hui Wu, Matrix Yao, Albert Hu, Gaofeng Sun, Xiaokun Yu, Jian Tang
mathjax: true
---

* content
{:toc}

##### Abstract
Lung nodule proposals generation is the primary step of lung nodule detection and has received much attention in recent years . In this paper, we first construct a model of 3-dimension Convolutional Neural Network (3D CNN) to generate lung nodule proposals, which can achieve the state-of-the-art performance. Then, we analyze a series of key problems concerning the training performance and efficiency. Firstly, we train the 3D CNN model with data in different resolutions and find out that models trained by high resolution input data achieve better lung nodule proposals generation performances especially for nodules in too small sizes, while consumes much more memory at the same time. Then, we analyze the memory consumptions on different platforms and the experimental results indicate that CPU architecture can provide us with larger memory and enables us to explore more possibilities of 3D applications. We implement the 3D CNN model on CPU platform and propose an Intel Extended-Caffe framework which supports many highly-efficient 3D computations, which is opened source at this https URL

##### Abstract (translated by Google)
肺结节提案的生成是肺结节检测的主要步骤，近年来备受关注。本文首先构建三维卷积神经网络（3D CNN）模型，生成肺结节提议，达到最佳的性能。然后，我们分析了一系列关于培训绩效和效率的关键问题。首先对不同分辨率数据的三维CNN模型进行训练，发现经高分辨率输入数据训练的模型，肺结节建议生成性能较好，尤其对于体积过小的结节，同时消耗更多的内存。然后，我们分析不同平台上的内存消耗情况，实验结果表明CPU架构可以为我们提供更大的内存，使我们能够探索更多的3D应用的可能性。我们在CPU平台上实现了3D CNN模型，并提出了一个支持许多高效3D计算的Intel Extended-Caffe框架，这个框架在这个https URL中是开源的

##### URL
[https://arxiv.org/abs/1802.02179](https://arxiv.org/abs/1802.02179)

##### PDF
[https://arxiv.org/pdf/1802.02179](https://arxiv.org/pdf/1802.02179)

