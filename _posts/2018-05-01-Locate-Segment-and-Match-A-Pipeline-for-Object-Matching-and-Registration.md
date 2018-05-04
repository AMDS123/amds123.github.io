---
layout: post
title: "Locate, Segment and Match: A Pipeline for Object Matching and Registration"
date: 2018-05-01 07:50:25
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation CNN Detection
author: Deepak Mishra, Rajeev Ranjan, Santanu Chaudhury, Mukul Sarkar, Arvinder Singh Soin
mathjax: true
---

* content
{:toc}

##### Abstract
Image registration requires simultaneous processing of multiple images to match the keypoints or landmarks of the contained objects. These images often come from different modalities for example CT and Ultrasound (US), and pose the challenge of establishing one to one correspondence. In this work, a novel pipeline of convolutional neural networks is developed to perform the desired registration. The complete objective is divided into three parts: localization of the object of interest, segmentation and matching transformation. Most of the existing approaches skip the localization step and are prone to fail in general scenarios. We overcome this challenge through detection which also establishes initial correspondence between the images. A modified version of single shot multibox detector is used for this purpose. The detected region is cropped and subsequently segmented to generate a mask corresponding to the desired object. The mask is used by a spatial transformer network employing thin plate spline deformation to perform the desired registration. Initial experiments on MNIST and Caltech-101 datasets show that the proposed model is able to accurately match the segmented images. The proposed framework is extended to the registration of CT and US images, which is free from any data specific assumptions and has better generalization capability as compared to the existing rule based/classical approaches.

##### Abstract (translated by Google)
图像注册需要同时处理多个图像以匹配包含对象的关键点或地标。这些图像通常来自不同的模态，例如CT和超声波（US），并且构成建立一对一通信的挑战。在这项工作中，一种新型的卷积神经网络管道被开发来执行所需的配准。完整的目标分为三个部分：感兴趣对象的本地化，分割和匹配转换。大多数现有方法都会跳过本地化步骤，并且在一般情况下很容易失败。我们通过检测来克服这个挑战，该检测也建立图像之间的初始对应关系。为此目的使用修改后的单发多盒探测器。检测到的区域被裁剪并且随后被分割以生成对应于期望对象的遮罩。掩模由采用薄板样条变形的空间变换器网络用于执行期望的配准。在MNIST和Caltech-101数据集上的初始实验表明，所提出的模型能够精确地匹配分割的图像。所提出的框架被扩展到CT和美国图像的注册，其与任何数据具体假设无关并且与现有的基于规则/经典方法相比具有更好的泛化能力。

##### URL
[https://arxiv.org/abs/1805.00223](https://arxiv.org/abs/1805.00223)

##### PDF
[https://arxiv.org/pdf/1805.00223](https://arxiv.org/pdf/1805.00223)

