---
layout: post
title: "Learning Analysis-by-Synthesis for 6D Pose Estimation in RGB-D Images"
date: 2015-08-19 07:24:14
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN
author: Alexander Krull, Eric Brachmann, Frank Michel, Michael Ying Yang, Stefan Gumhold, Carsten Rother
mathjax: true
---

* content
{:toc}

##### Abstract
Analysis-by-synthesis has been a successful approach for many tasks in computer vision, such as 6D pose estimation of an object in an RGB-D image which is the topic of this work. The idea is to compare the observation with the output of a forward process, such as a rendered image of the object of interest in a particular pose. Due to occlusion or complicated sensor noise, it can be difficult to perform this comparison in a meaningful way. We propose an approach that "learns to compare", while taking these difficulties into account. This is done by describing the posterior density of a particular object pose with a convolutional neural network (CNN) that compares an observed and rendered image. The network is trained with the maximum likelihood paradigm. We observe empirically that the CNN does not specialize to the geometry or appearance of specific objects, and it can be used with objects of vastly different shapes and appearances, and in different backgrounds. Compared to state-of-the-art, we demonstrate a significant improvement on two different datasets which include a total of eleven objects, cluttered background, and heavy occlusion.

##### Abstract (translated by Google)
综合分析已经成为计算机视觉中许多任务的成功方法，例如RGB-D图像中的对象的6D姿态估计，这是本文的主题。这个想法是将观察结果与一个前进过程的输出进行比较，例如在一个特定的姿势中的感兴趣的对象的渲染图像。由于阻塞或传感器噪声的复杂，可能难以以有意义的方式执行这种比较。我们提出一个“学会比较”的方法，同时考虑到这些困难。这是通过用卷积神经网络（CNN）描述特定对象姿态的后验密度来完成的，所述卷积神经网络比较观察和渲染的图像。网络训练的最大似然范式。我们经验地观察到，CNN并不专注于特定物体的几何形状或外观，而是可以用于形状和外观大不相同，背景不同的物体。与最先进的技术相比，我们在两个不同的数据集上展示了显着的改进，这些数据集总共包括十一个对象，杂乱的背景和重度遮挡。

##### URL
[https://arxiv.org/abs/1508.04546](https://arxiv.org/abs/1508.04546)

##### PDF
[https://arxiv.org/pdf/1508.04546](https://arxiv.org/pdf/1508.04546)

