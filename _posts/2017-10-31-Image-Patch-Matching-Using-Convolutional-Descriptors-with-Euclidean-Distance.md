---
layout: post
title: "Image Patch Matching Using Convolutional Descriptors with Euclidean Distance"
date: 2017-10-31 07:48:11
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Classification Detection
author: Iaroslav Melekhov, Juho Kannala, Esa Rahtu
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we propose a neural network based image descriptor suitable for image patch matching, which is an important task in many computer vision applications. Our approach is influenced by recent success of deep convolutional neural networks (CNNs) in object detection and classification tasks. We develop a model which maps the raw input patch to a low dimensional feature vector so that the distance between representations is small for similar patches and large otherwise. As a distance metric we utilize L2 norm, i.e. Euclidean distance, which is fast to evaluate and used in most popular hand-crafted descriptors, such as SIFT. According to the results, our approach outperforms state-of-the-art L2-based descriptors and can be considered as a direct replacement of SIFT. In addition, we conducted experiments with batch normalization and histogram equalization as a preprocessing method of the input data. The results confirm that these techniques further improve the performance of the proposed descriptor. Finally, we show promising preliminary results by appending our CNNs with recently proposed spatial transformer networks and provide a visualisation and interpretation of their impact.

##### Abstract (translated by Google)
在这项工作中，我们提出了一个基于神经网络的图像描述符适合图像补丁匹配，这是许多计算机视觉应用中的一个重要任务。我们的方法受深度卷积神经网络（CNN）在对象检测和分类任务中的最近成功的影响。我们开发了一个模型，将原始输入贴图映射到一个低维特征向量，以便相似补丁的表示之间的距离较小，否则较大。作为距离度量，我们使用L2范数，即欧几里德距离，它是快速评估和使用在最流行的手工描述符，如SIFT。根据结果​​，我们的方法胜过了最先进的基于L2的描述符，可以被认为是SIFT的直接替代。另外，我们还进行了批量归一化和直方图均衡的实验，作为输入数据的预处理方法。结果证实，这些技术进一步改善了所提出的描述符的性能。最后，我们通过在最近提出的空间变换网络上附加我们的CNN来显示有希望的初步结果，并提供对其影响的可视化和解释。

##### URL
[https://arxiv.org/abs/1710.11359](https://arxiv.org/abs/1710.11359)

##### PDF
[https://arxiv.org/pdf/1710.11359](https://arxiv.org/pdf/1710.11359)

