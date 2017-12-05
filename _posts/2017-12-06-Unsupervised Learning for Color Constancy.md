---
layout: post
title: 'Unsupervised Learning for Color Constancy'
date: 2017-12-06 02:05:30
categories: arXiv_CV
tags: arXiv_CV
author: Nikola Banić, Sven Lončarić
---

* content
{:toc}

##### Abstract
Most digital camera pipelines use color constancy methods to reduce the influence of illumination and camera sensor on the colors of scene objects. The highest accuracy of color correction is obtained with learning-based color constancy methods, but they require a significant amount of calibrated training images with known ground-truth illumination. Such calibration is time consuming, preferably done for each sensor individually, and therefore a major bottleneck in acquiring high color constancy accuracy. Statistics-based methods do not require calibrated training images, but they are less accurate. In this paper an unsupervised learning-based method is proposed that learns its parameter values after approximating the unknown ground-truth illumination of the training images, thus avoiding calibration. In terms of accuracy the proposed method outperforms all statistics-based and many learning-based methods. An extension of the method is also proposed, which learns the needed parameters from non-calibrated images taken with one sensors and which can then be successfully applied to images taken with another sensor. This effectively enables inter-camera unsupervised learning for color constancy. Additionally, a new high quality color constancy benchmark dataset with 1365 calibrated images is created, used for testing, and made publicly available. The results are presented and discussed. The source code and the dataset are available at this http URL

##### Abstract (translated by Google)
大多数数码相机管线采用色彩恒常方法来减少照明和相机传感器对场景物体颜色的影响。色彩校正的最高准确度是通过基于学习的色彩恒常方法获得的，但是它们需要大量具有已知地面真实照明的校准训练图像。这种校准是耗时的，最好对每个传感器单独进行，因此是获得高颜色恒定精度的主要瓶颈。基于统计学的方法不需要校准的训练图像，但是它们不太准确。本文提出了一种无监督学习的方法，在逼近训练图像的未知地面实况照度之后，学习其参数值，从而避免了校准。在准确性方面，所提出的方法优于所有基于统计的和许多基于学习的方法。还提出了该方法的扩展，其从一个传感器拍摄的非校准图像中学习所需的参数，然后可以成功地将其应用于用另一个传感器拍摄的图像。这有效地使相机之间的无监督学习颜色恒常。此外，还创建了一个新的高质量色彩恒定性基准数据集，包含1365个校准图像，用于测试并公开发布。结果被提出和讨论。源代码和数据集可以在这个http URL中找到

##### URL
[https://arxiv.org/abs/1712.00436](https://arxiv.org/abs/1712.00436)

