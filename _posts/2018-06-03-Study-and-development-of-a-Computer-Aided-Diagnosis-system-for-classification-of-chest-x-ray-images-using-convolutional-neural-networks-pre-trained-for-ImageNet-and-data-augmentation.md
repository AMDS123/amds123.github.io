---
layout: post
title: "Study and development of a Computer-Aided Diagnosis system for classification of chest x-ray images using convolutional neural networks pre-trained for ImageNet and data augmentation"
date: 2018-06-03 17:31:42
categories: arXiv_CV
tags: arXiv_CV CNN Transfer_Learning Classification
author: Vinicius Pavanelli Vianna
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural networks (ConvNets) are the actual standard for image recognizement and classification. On the present work we develop a Computer Aided-Diagnosis (CAD) system using ConvNets to classify a x-rays chest images dataset in two groups: Normal and Pneumonia. The study uses ConvNets models available on the PyTorch platform: AlexNet, SqueezeNet, ResNet and Inception. We initially use three training styles: complete from scratch using random initialization, using a pre-trained ImageNet model training only the last layer adapted to our problem (transfer learning) and a pre-trained model modified training all the classifying layers of the model (fine tuning). The last strategy of training used is with data augmentation techniques that avoid over fitting problems on ConvNets yielding the better results on this study

##### Abstract (translated by Google)
卷积神经网络（ConvNets）是图像识别和分类的实际标准。在目前的工作中，我们开发了一个使用ConvNets的计算机辅助诊断（CAD）系统，将X射线胸部图像数据集分为两组：正常组和肺炎组。该研究使用PyTorch平台上提供的ConvNets模型：AlexNet，SqueezeNet，ResNet和Inception。我们最初使用三种训练样式：使用随机初始化从头开始，使用预先训练的ImageNet模型训练仅适用于我们问题的最后一层（传输学习）和预先训练的模型修改训练模型的所有分类层（微调）。使用的最后一种培训策略是使用数据增强技术，避免ConvNets上的过度拟合问题，从而在本研究中产生更好的结果

##### URL
[http://arxiv.org/abs/1806.00839](http://arxiv.org/abs/1806.00839)

##### PDF
[http://arxiv.org/pdf/1806.00839](http://arxiv.org/pdf/1806.00839)

