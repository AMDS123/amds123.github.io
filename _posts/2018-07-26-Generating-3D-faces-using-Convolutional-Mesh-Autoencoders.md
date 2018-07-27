---
layout: post
title: "Generating 3D faces using Convolutional Mesh Autoencoders"
date: 2018-07-26 17:53:50
categories: arXiv_CV
tags: arXiv_CV Face Tracking CNN
author: Anurag Ranjan, Timo Bolkart, Soubhik Sanyal, Michael J. Black
mathjax: true
---

* content
{:toc}

##### Abstract
Learned 3D representations of human faces are useful for computer vision problems such as 3D face tracking and reconstruction from images, as well as graphics applications such as character generation and animation. Traditional models learn a latent representation of a face using linear subspaces or higher-order tensor generalizations. Due to this linearity, they can not capture extreme deformations and non-linear expressions. To address this, we introduce a versatile model that learns a non-linear representation of a face using spectral convolutions on a mesh surface. We introduce mesh sampling operations that enable a hierarchical mesh representation that captures non-linear variations in shape and expression at multiple scales within the model. In a variational setting, our model samples diverse realistic 3D faces from a multivariate Gaussian distribution. Our training data consists of 20,466 meshes of extreme expressions captured over 12 different subjects. Despite limited training data, our trained model outperforms state-of-the-art face models with 50% lower reconstruction error, while using 75% fewer parameters. We also show that, replacing the expression space of an existing state-of-the-art face model with our autoencoder, achieves a lower reconstruction error. Our data, model and code are available at <a href="http://github.com/anuragranj/coma.">this http URL</a>

##### Abstract (translated by Google)
人脸的学习3D表示对于计算机视觉问题是有用的，例如3D面部跟踪和从图像重建，以及诸如角色生成和动画的图形应用。传统模型使用线性子空间或高阶张量概括来学习面部的潜在表示。由于这种线性，它们无法捕获极端变形和非线性表达式。为了解决这个问题，我们引入了一个多功能模型，该模型使用网格表面上的光谱卷积来学习面部的非线性表示。我们引入了网格采样操作，这种操作能够实现分层网格表示，捕获模型中多个尺度的形状和表达的非线性变化。在变分设置中，我们的模型从多元高斯分布中采样不同的逼真3D面。我们的训练数据包括在12个不同科目中捕获的20,466个极端表情网格。尽管训练数据有限，但我们训练有素的模型优于最先进的面部模型，重建误差降低50％，而参数减少75％。我们还表明，用我们的自动编码器替换现有最先进的人脸模型的表达空间，可以实现较低的重建误差。我们的数据，模型和代码可在<a href="http://github.com/anuragranj/coma.">此http URL </a>上找到

##### URL
[http://arxiv.org/abs/1807.10267](http://arxiv.org/abs/1807.10267)

##### PDF
[http://arxiv.org/pdf/1807.10267](http://arxiv.org/pdf/1807.10267)

