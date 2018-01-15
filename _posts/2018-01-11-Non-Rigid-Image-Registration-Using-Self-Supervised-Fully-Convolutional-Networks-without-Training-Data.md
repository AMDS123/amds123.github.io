---
layout: post
title: "Non-Rigid Image Registration Using Self-Supervised Fully Convolutional Networks without Training Data"
date: 2018-01-11 22:58:48
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Hongming Li, Yong Fan
mathjax: true
---

* content
{:toc}

##### Abstract
A novel non-rigid image registration algorithm is built upon fully convolutional networks (FCNs) to optimize and learn spatial transformations between pairs of images to be registered in a self-supervised learning framework. Different from most existing deep learning based image registration methods that learn spatial transformations from training data with known corresponding spatial transformations, our method directly estimates spatial transformations between pairs of images by maximizing an image-wise similarity metric between fixed and deformed moving images, similar to conventional image registration algorithms. The image registration is implemented in a multi-resolution image registration framework to jointly optimize and learn spatial transformations and FCNs at different spatial resolutions with deep self-supervision through typical feedforward and backpropagation computation. The proposed method has been evaluated for registering 3D structural brain magnetic resonance (MR) images and obtained better performance than state-of-the-art image registration algorithms.

##### Abstract (translated by Google)
一种新的非刚性图像配准算法是建立在完全卷积网络（FCN）上，以优化和学习在自监督学习框架中登记的图像对之间的空间变换。与大多数现有的基于深度学习的图像配准方法不同，后者通过已知的相应空间变换从训练数据中学习空间变换，我们的方法通过最大化固定和变形运动图像之间的图像相似性度量来直接估计图像对之间的空间变换，传统的图像配准算法。在多分辨率图像配准框架中实现图像配准，通过典型的前馈和后向传播计算，以不同的空间分辨率，深度自监督的方式联合优化和学习空间变换和FCNs。所提出的方法已经被评估为登记三维结构脑磁共振（MR）图像，并获得比现有技术的图像配准算法更好的性能。

##### URL
[http://arxiv.org/abs/1801.04012](http://arxiv.org/abs/1801.04012)

##### PDF
[http://arxiv.org/pdf/1801.04012](http://arxiv.org/pdf/1801.04012)

