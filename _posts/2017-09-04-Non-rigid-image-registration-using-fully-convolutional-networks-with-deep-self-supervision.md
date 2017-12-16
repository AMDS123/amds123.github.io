---
layout: post
title: "Non-rigid image registration using fully convolutional networks with deep self-supervision"
date: 2017-09-04 03:22:20
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Deep_Learning
author: Hongming Li, Yong Fan
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel non-rigid image registration algorithm that is built upon fully convolutional networks (FCNs) to optimize and learn spatial transformations between pairs of images to be registered. Different from most existing deep learning based image registration methods that learn spatial transformations from training data with known corresponding spatial transformations, our method directly estimates spatial transformations between pairs of images by maximizing an image-wise similarity metric between fixed and deformed moving images, similar to conventional image registration algorithms. At the same time, our method also learns FCNs for encoding the spatial transformations at the same spatial resolution of images to be registered, rather than learning coarse-grained spatial transformation information. The image registration is implemented in a multi-resolution image registration framework to jointly optimize and learn spatial transformations and FCNs at different resolutions with deep self-supervision through typical feedforward and backpropagation computation. Since our method simultaneously optimizes and learns spatial transformations for the image registration, our method can be directly used to register a pair of images, and the registration of a set of images is also a training procedure for FCNs so that the trained FCNs can be directly adopted to register new images by feedforward computation of the learned FCNs without any optimization. The proposed method has been evaluated for registering 3D structural brain magnetic resonance (MR) images and obtained better performance than state-of-the-art image registration algorithms.

##### Abstract (translated by Google)
我们提出了一个新的非刚性图像配准算法，建立在完全卷积网络（FCNs）上，以优化和学习要配准的图像对之间的空间变换。与大多数现有的基于深度学习的图像配准方法不同，该方法利用已知的相应空间变换从训练数据中学习空间变换，我们的方法通过最大化固定和变形运动图像之间的图像相似性度量来直接估计图像对之间的空间变换，传统的图像配准算法。同时，我们的方法也学习FCNs在相同的空间分辨率的图像进行编码空间转换注册，而不是学习粗粒度的空间转换信息。在多分辨率图像配准框架中实现图像配准，通过典型的前馈和后向传播计算，以不同的分辨率，深度自监督的方式联合优化和学习空间转换和FCNs。由于我们的方法同时优化和学习图像配准的空间变换，我们的方法可以直接用来配准一对图像，一套图像的配准也是一个FCN的训练过程，使得训练的FCN可以直接通过对所学习的FCN的前馈计算来注册新的图像而无需任何优化。所提出的方法已经被评估为登记三维结构脑磁共振（MR）图像，并获得比现有技术的图像配准算法更好的性能。

##### URL
[https://arxiv.org/abs/1709.00799](https://arxiv.org/abs/1709.00799)

##### PDF
[https://arxiv.org/pdf/1709.00799](https://arxiv.org/pdf/1709.00799)

