---
layout: post
title: "Multi-function Convolutional Neural Networks for Improving Image Classification Performance"
date: 2018-05-30 03:14:03
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification
author: Luna M. Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Traditional Convolutional Neural Networks (CNNs) typically use the same activation function (usually ReLU) for all neurons with non-linear mapping operations. For example, the deep convolutional architecture Inception-v4 uses ReLU. To improve the classification performance of traditional CNNs, a new "Multi-function Convolutional Neural Network" (MCNN) is created by using different activation functions for different neurons. For $n$ neurons and $m$ different activation functions, there are a total of $m^n-m$ MCNNs and only $m$ traditional CNNs. Therefore, the best model is very likely to be chosen from MCNNs because there are $m^n-2m$ more MCNNs than traditional CNNs. For performance analysis, two different datasets for two applications (classifying handwritten digits from the MNIST database and classifying brain MRI images into one of the four stages of Alzheimer's disease (AD)) are used. For both applications, an activation function is randomly selected for each layer of a MCNN. For the AD diagnosis application, MCNNs using a newly created multi-function Inception-v4 architecture are constructed. Overall, simulations show that MCNNs can outperform traditional CNNs in terms of multi-class classification accuracy for both applications. An important future research work will be to efficiently select the best MCNN from $m^n-m$ candidate MCNNs. Current CNN software only provides users with partial functionality of MCNNs since different layers can use different activation functions but not individual neurons in the same layer. Thus, modifying current CNN software systems such as ResNets, DenseNets, and Dual Path Networks by using multiple activation functions and developing more effective and faster MCNN software systems and tools would be very useful to solve difficult practical image classification problems.

##### Abstract (translated by Google)
传统的卷积神经网络（CNN）通常对所有具有非线性映射操作的神经元使用相同的激活函数（通常是ReLU）。例如，深度卷积体系结构Inception-v4使用ReLU。为了提高传统CNN的分类性能，通过对不同神经元使用不同的激活函数，创建了一个新的“多功能卷积神经网络”（MCNN）。对于$ n $神经元和$ m $不同的激活函数，总共有$ m ^ n-m $ MCNNs和$ m $传统的CNN。因此，最好的模型很可能从MCNN中选择，因为MCNN比传统的CNN多$ m ^ n-2m $。对于性能分析，使用两个不同的数据集（两个应用程序分类MNIST数据库中的手写数字，并将脑MRI图像分为阿尔茨海默病（AD）四个阶段之一）。对于这两种应用程序，MCNN的每一层随机选择一个激活函数。对于AD诊断应用程序，构建使用新创建的多功能Inception-v4体系结构的MCNN。总体而言，仿真表明MCNN在两种应用的多类分类精度方面可以胜过传统的CNN。一项重要的未来研究工作将是从$ m ^ m-m候选MCNN有效地选择最佳MCNN。目前的CNN软件仅向用户提供MCNN的部分功能，因为不同的层可以使用不同的激活功能，但不是同一层中的单个神经元。因此，通过使用多种激活功能并开发更有效和更快的MCNN软件系统和工具来修改当前的CNN软件系统（例如ResNets，DenseNets和双路径网络）将对解决困难的实际图像分类问题非常有用。

##### URL
[https://arxiv.org/abs/1805.11788](https://arxiv.org/abs/1805.11788)

##### PDF
[https://arxiv.org/pdf/1805.11788](https://arxiv.org/pdf/1805.11788)

