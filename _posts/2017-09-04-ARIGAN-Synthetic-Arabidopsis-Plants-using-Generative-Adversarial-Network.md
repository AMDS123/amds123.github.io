---
layout: post
title: "ARIGAN: Synthetic Arabidopsis Plants using Generative Adversarial Network"
date: 2017-09-04 13:12:58
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation GAN CNN Deep_Learning
author: Mario Valerio Giuffrida, Hanno Scharr, Sotirios A Tsaftaris
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, there has been an increasing interest in image-based plant phenotyping, applying state-of-the-art machine learning approaches to tackle challenging problems, such as leaf segmentation (a multi-instance problem) and counting. Most of these algorithms need labelled data to learn a model for the task at hand. Despite the recent release of a few plant phenotyping datasets, large annotated plant image datasets for the purpose of training deep learning algorithms are lacking. One common approach to alleviate the lack of training data is dataset augmentation. Herein, we propose an alternative solution to dataset augmentation for plant phenotyping, creating artificial images of plants using generative neural networks. We propose the Arabidopsis Rosette Image Generator (through) Adversarial Network: a deep convolutional network that is able to generate synthetic rosette-shaped plants, inspired by DCGAN (a recent adversarial network model using convolutional layers). Specifically, we trained the network using A1, A2, and A4 of the CVPPP 2017 LCC dataset, containing Arabidopsis Thaliana plants. We show that our model is able to generate realistic 128x128 colour images of plants. We train our network conditioning on leaf count, such that it is possible to generate plants with a given number of leaves suitable, among others, for training regression based models. We propose a new Ax dataset of artificial plants images, obtained by our ARIGAN. We evaluate this new dataset using a state-of-the-art leaf counting algorithm, showing that the testing error is reduced when Ax is used as part of the training data.

##### Abstract (translated by Google)
近年来，人们对基于图像的植物表型研究越来越感兴趣，他们运用最先进的机器学习方法来解决具有挑战性的问题，如叶片分割（多实例问题）和计数问题。大多数这些算法需要标记数据来学习手头任务的模型。尽管最近发布了一些植物表型数据集，但缺乏用于训练深度学习算法的大型注释植物图像数据集。减轻训练数据缺乏的一种常见方法是增加数据集。在这里，我们提出了一个替代解决方案数据集增加植物表型，创造人工图像植物使用生成神经网络。我们提出了拟南芥Rosette图像发生器（通过）敌对网络：深层卷积网络，能够产生合成玫瑰花状植物，启发DCGAN（最近的对抗网络模型使用卷积层）。具体而言，我们使用包含拟南芥拟南芥植物的CVPPP 2017 LCC数据集的A1，A2和A4来训练网络。我们显示我们的模型能够生成植物的逼真的128x128彩色图像。我们在叶数上训练我们的网络调节，从而有可能产生具有给定叶数的植物，适用于训练基于回归的模型。我们提出了由ARIGAN获得的人造植物图像的新Ax数据集。我们使用先进的叶计数算法评估这个新的数据集，显示当将Ax用作训练数据的一部分时，测试误差减少。

##### URL
[https://arxiv.org/abs/1709.00938](https://arxiv.org/abs/1709.00938)

##### PDF
[https://arxiv.org/pdf/1709.00938](https://arxiv.org/pdf/1709.00938)

