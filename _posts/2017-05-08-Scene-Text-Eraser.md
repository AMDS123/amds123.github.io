---
layout: post
title: "Scene Text Eraser"
date: 2017-05-08 08:28:34
categories: arXiv_CV
tags: arXiv_CV CNN Detection
author: Toshiki Nakamura, Anna Zhu, Keiji Yanai, Seiichi Uchida
mathjax: true
---

* content
{:toc}

##### Abstract
The character information in natural scene images contains various personal information, such as telephone numbers, home addresses, etc. It is a high risk of leakage the information if they are published. In this paper, we proposed a scene text erasing method to properly hide the information via an inpainting convolutional neural network (CNN) model. The input is a scene text image, and the output is expected to be text erased image with all the character regions filled up the colors of the surrounding background pixels. This work is accomplished by a CNN model through convolution to deconvolution with interconnection process. The training samples and the corresponding inpainting images are considered as teaching signals for training. To evaluate the text erasing performance, the output images are detected by a novel scene text detection method. Subsequently, the same measurement on text detection is utilized for testing the images in benchmark dataset ICDAR2013. Compared with direct text detection way, the scene text erasing process demonstrates a drastically decrease on the precision, recall and f-score. That proves the effectiveness of proposed method for erasing the text in natural scene images.

##### Abstract (translated by Google)
自然场景图像中的字符信息包含各种个人信息，例如电话号码，家庭地址等。如果发布信息，则泄漏信息的风险很高。在本文中，我们提出了一种场景文本擦除方法，通过修复卷积神经网络（CNN）模型来恰当地隐藏信息。输入是场景文本图像，并且输出预期是文本擦除图像，其中所有字符区域填充周围背景像素的颜色。这项工作是由一个CNN模型通过卷积到互联过程去卷积来完成的。训练样本和相应的修补图像被认为是训练的教学信号。为了评估文本擦除性能，通过新的场景文本检测方法来检测输出图像。随后，对文本检测的相同测量被用于测试基准数据集ICDAR2013中的图像。与直接文本检测方式相比，场景文本清除过程在精度，召回率和f分数上显示了大幅度的下降。这证明了提出的自然场景图像文本删除方法的有效性。

##### URL
[https://arxiv.org/abs/1705.02772](https://arxiv.org/abs/1705.02772)

##### PDF
[https://arxiv.org/pdf/1705.02772](https://arxiv.org/pdf/1705.02772)

