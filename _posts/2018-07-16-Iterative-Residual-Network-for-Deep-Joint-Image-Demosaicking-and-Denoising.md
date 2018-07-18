---
layout: post
title: "Iterative Residual Network for Deep Joint Image Demosaicking and Denoising"
date: 2018-07-16 08:17:46
categories: arXiv_CV
tags: arXiv_CV Regularization Optimization Deep_Learning
author: Filippos Kokkinos, Stamatios Lefkimmiatis
mathjax: true
---

* content
{:toc}

##### Abstract
Modern digital cameras rely on sequential execution of separate image processing steps to produce realistic images. The first two steps are usually related to denoising and demosaicking where the former aims to reduce noise from the sensor and the latter converts a series of light intensity readings to color images. Modern approaches try to jointly solve these problems, i.e joint denoising-demosaicking which is an inherently ill-posed problem given that two-thirds of the intensity information are missing and the rest are perturbed by noise. While there are several machine learning systems that have been recently introduced to solve this problem, in this work we propose a novel algorithm which is inspired by powerful classical image regularization methods, large-scale optimization and deep learning techniques. Consequently, our derived neural network has a transparent and clear interpretation compared to other black-box data-driven approaches. Our extensive experimentation line demonstrates that our proposed network outperforms any previous approaches on both noisy and noise-free data across many different datasets. This improvement in reconstruction quality is attributed to the principled way we design our network architecture, which as a result requires fewer trainable parameters than the current state-of-the-art solution and furthermore can be efficiently trained by using a significantly smaller number of training data than existing deep demosaicking networks.

##### Abstract (translated by Google)
现代数码相机依赖于单独的图像处理步骤的顺序执行以产生逼真的图像。前两个步骤通常与去噪和去马赛克相关，其中前者旨在减少来自传感器的噪声，后者将一系列光强度读数转换为彩色图像。现代方法试图联合解决这些问题，即联合去噪 - 去马赛克，这是一个固有的不适定问题，因为三分之二的强度信息丢失，其余的都受到噪音的干扰。虽然最近引入了几种机器学习系统来解决这个问题，但在这项工作中，我们提出了一种新的算法，其灵感来自强大的经典图像正则化方法，大规模优化和深度学习技术。因此，与其他黑盒数据驱动方法相比，我们的派生神经网络具有透明和清晰的解释。我们广泛的实验线表明，我们提出的网络在许多不同数据集上的噪声和无噪声数据上均优于任何先前的方法。重建质量的这种改进归功于我们设计网络架构的原则性方式，因此需要比当前最先进的解决方案更少的可训练参数，并且通过使用少得多的训练可以有效地训练数据比现有的深度去马赛克网络。

##### URL
[http://arxiv.org/abs/1807.06403](http://arxiv.org/abs/1807.06403)

##### PDF
[http://arxiv.org/pdf/1807.06403](http://arxiv.org/pdf/1807.06403)

