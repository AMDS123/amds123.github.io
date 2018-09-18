---
layout: post
title: "A Deep Learning Framework for Unsupervised Affine and Deformable Image Registration"
date: 2018-09-17 11:14:54
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Bob D. de Vos, Floris F. Berendsen, Max A. Viergever, Hessam Sokooti, Marius Staring, Ivana Isgum
mathjax: true
---

* content
{:toc}

##### Abstract
Image registration, the process of aligning two or more images, is the core technique of many (semi-)automatic medical image analysis tasks. Recent studies have shown that deep learning methods, notably convolutional neural networks (ConvNets), can be used for image registration. Thus far training of ConvNets for registration was supervised using predefined example registrations. However, obtaining example registrations is not trivial. To circumvent the need for predefined examples, and thereby to increase convenience of training ConvNets for image registration, we propose the Deep Learning Image Registration (DLIR) framework for \textit{unsupervised} affine and deformable image registration. In the DLIR framework ConvNets are trained for image registration by exploiting image similarity analogous to conventional intensity-based image registration. After a ConvNet has been trained with the DLIR framework, it can be used to register pairs of unseen images in one shot. We propose flexible ConvNets designs for affine image registration and for deformable image registration. By stacking multiple of these ConvNets into a larger architecture, we are able to perform coarse-to-fine image registration. We show for registration of cardiac cine MRI and registration of chest CT that performance of the DLIR framework is comparable to conventional image registration while being several orders of magnitude faster.

##### Abstract (translated by Google)
图像配准是对齐两个或多个图像的过程，是许多（半）自动医学图像分析任务的核心技术。最近的研究表明，深度学习方法，特别是卷积神经网络（ConvNets），可用于图像配准。迄今为止，使用预定义的示例注册来监督ConvNets的注册培训。但是，获得示例注册并非易事。为了避免对预定义示例的需求，从而增加培训ConvNets进行图像配准的便利性，我们提出了用于\ textit {无监督}仿射和可变形图像配准的深度学习图像配准（DLIR）框架。在DLIR框架中，通过利用类似于传统的基于强度的图像配准的图像相似性来训练ConvNets用于图像配准。在使用DLIR框架训练ConvNet之后，它可以用于一次注册一对看不见的图像。我们提出灵活的ConvNets设计，用于仿射图像配准和可变形图像配准。通过将多个这些ConvNets堆叠到更大的架构中，我们能够执行从粗到细的图像配准。我们展示了心脏电影MRI的登记和胸部CT的登记，DLIR框架的性能与传统的图像登记相当，同时快了几个数量级。

##### URL
[http://arxiv.org/abs/1809.06130](http://arxiv.org/abs/1809.06130)

##### PDF
[http://arxiv.org/pdf/1809.06130](http://arxiv.org/pdf/1809.06130)

