---
layout: post
title: "3DMatch: Learning Local Geometric Descriptors from RGB-D Reconstructions"
date: 2017-04-09 19:56:05
categories: arXiv_CV
tags: arXiv_CV Face
author: Andy Zeng, Shuran Song, Matthias Nießner, Matthew Fisher, Jianxiong Xiao, Thomas Funkhouser
mathjax: true
---

* content
{:toc}

##### Abstract
Matching local geometric features on real-world depth images is a challenging task due to the noisy, low-resolution, and incomplete nature of 3D scan data. These difficulties limit the performance of current state-of-art methods, which are typically based on histograms over geometric properties. In this paper, we present 3DMatch, a data-driven model that learns a local volumetric patch descriptor for establishing correspondences between partial 3D data. To amass training data for our model, we propose a self-supervised feature learning method that leverages the millions of correspondence labels found in existing RGB-D reconstructions. Experiments show that our descriptor is not only able to match local geometry in new scenes for reconstruction, but also generalize to different tasks and spatial scales (e.g. instance-level object model alignment for the Amazon Picking Challenge, and mesh surface correspondence). Results show that 3DMatch consistently outperforms other state-of-the-art approaches by a significant margin. Code, data, benchmarks, and pre-trained models are available online at this http URL

##### Abstract (translated by Google)
由于3D扫描数据的嘈杂，低分辨率和不完整的性质，匹配真实世界深度图像上的局部几何特征是具有挑战性的任务。这些困难限制了当前最先进的方法的性能，这些方法通常基于几何特性上的直方图。在本文中，我们提出3DMatch，一个数据驱动的模型，学习局部体积补丁描述符建立部分三维数据之间的对应关系。为了丰富我们的模型的训练数据，我们提出了一种自我监督的特征学习方法，利用现有的RGB-D重建中发现的数以百万计的通信标签。实验表明，我们的描述符不仅可以匹配新场景中的局部几何体进行重构，而且还可以推广到不同的任务和空间尺度（例如，亚马逊挑选挑战的实例级对象模型对齐和网格表面对应）。结果显示，3DMatch一贯优于其他最先进的方法。代码，数据，基准和预先训练好的模型可以在这个http URL上在线获得

##### URL
[https://arxiv.org/abs/1603.08182](https://arxiv.org/abs/1603.08182)

##### PDF
[https://arxiv.org/pdf/1603.08182](https://arxiv.org/pdf/1603.08182)

