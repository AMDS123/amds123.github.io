---
layout: post
title: "Coupled IGMM-GANs for deep multimodal anomaly detection in human mobility data"
date: 2018-09-08 01:11:10
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Detection
author: Kathryn Gray, Daniel Smolyak, Sarkhan Badirli, George Mohler
mathjax: true
---

* content
{:toc}

##### Abstract
Detecting anomalous activity in human mobility data has a number of applications including road hazard sensing, telematic based insurance, and fraud detection in taxi services and ride sharing. In this paper we address two challenges that arise in the study of anomalous human trajectories: 1) a lack of ground truth data on what defines an anomaly and 2) the dependence of existing methods on significant pre-processing and feature engineering. While generative adversarial networks seem like a natural fit for addressing these challenges, we find that existing GAN based anomaly detection algorithms perform poorly due to their inability to handle multimodal patterns. For this purpose we introduce an infinite Gaussian mixture model coupled with (bi-directional) generative adversarial networks, IGMM-GAN, that is able to generate synthetic, yet realistic, human mobility data and simultaneously facilitates multimodal anomaly detection. Through estimation of a generative probability density on the space of human trajectories, we are able to generate realistic synthetic datasets that can be used to benchmark existing anomaly detection methods. The estimated multimodal density also allows for a natural definition of outlier that we use for detecting anomalous trajectories. We illustrate our methodology and its improvement over existing GAN anomaly detection on several human mobility datasets, along with MNIST.

##### Abstract (translated by Google)
检测人类移动数据中的异常活动具有许多应用，包括道路危险感测，基于远程信息处理的保险以及出租车服务和乘车共享中的欺诈检测。在本文中，我们讨论了人类异常轨迹研究中出现的两个挑战：1）缺乏关于什么定义异常的地面实况数据; 2）现有方法对重要预处理和特征工程的依赖性。虽然生成对抗性网络似乎很适合解决这些挑战，但我们发现现有的基于GAN的异常检测算法由于无法处理多模式模式而表现不佳。为此，我们引入了无限高斯混合模型，该模型与（双向）生成对抗网络IGMM-GAN相结合，能够生成合成但逼真的人类移动数据，同时促进多模态异常检测。通过估计人类轨迹空间上的生成概率密度，我们能够生成真实的合成数据集，可用于对现有的异常检测方法进行基准测试。估计的多峰密度还允许我们用于检测异常轨迹的异常值的自然定义。我们演示了我们的方法及其对几个人类移动数据集的现有GAN异常检测以及MNIST的改进。

##### URL
[https://arxiv.org/abs/1809.02728](https://arxiv.org/abs/1809.02728)

##### PDF
[https://arxiv.org/pdf/1809.02728](https://arxiv.org/pdf/1809.02728)

