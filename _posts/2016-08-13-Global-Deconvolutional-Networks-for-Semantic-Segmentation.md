---
layout: post
title: "Global Deconvolutional Networks for Semantic Segmentation"
date: 2016-08-13 08:54:42
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Image_Classification Semantic_Segmentation Classification Prediction Recognition
author: Vladimir Nekrasov, Janghoon Ju, Jaesik Choi
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic image segmentation is a principal problem in computer vision, where the aim is to correctly classify each individual pixel of an image into a semantic label. Its widespread use in many areas, including medical imaging and autonomous driving, has fostered extensive research in recent years. Empirical improvements in tackling this task have primarily been motivated by successful exploitation of Convolutional Neural Networks (CNNs) pre-trained for image classification and object recognition. However, the pixel-wise labelling with CNNs has its own unique challenges: (1) an accurate deconvolution, or upsampling, of low-resolution output into a higher-resolution segmentation mask and (2) an inclusion of global information, or context, within locally extracted features. To address these issues, we propose a novel architecture to conduct the equivalent of the deconvolution operation globally and acquire dense predictions. We demonstrate that it leads to improved performance of state-of-the-art semantic segmentation models on the PASCAL VOC 2012 benchmark, reaching 74.0% mean IU accuracy on the test set.

##### Abstract (translated by Google)
语义图像分割是计算机视觉中的主要问题，其目的是将图像的每个单独像素正确分类为语义标签。它在包括医学成像和自动驾驶在内的许多领域的广泛使用，近年来促成了广泛的研究。在处理这一任务方面的经验性改进主要是由成功利用卷积神经网络（CNN）预先训练用于图像分类和目标识别的动机。然而，使用CNN进行像素标记还有其独特的挑战：（1）将低分辨率输出精确的去卷积或上采样到更高分辨率的分割掩模中;（2）包含全局信息或上下文，在本地提取的功能。为了解决这些问题，我们提出了一种新颖的架构来进行全局反褶积操作的等价操作，并获得密集的预测。我们证明，它导致了PASCAL VOC 2012基准测试中最先进的语义分割模型的性能提高，在测试集上达到了74.0％的平均IU准确度。

##### URL
[https://arxiv.org/abs/1602.03930](https://arxiv.org/abs/1602.03930)

##### PDF
[https://arxiv.org/pdf/1602.03930](https://arxiv.org/pdf/1602.03930)

