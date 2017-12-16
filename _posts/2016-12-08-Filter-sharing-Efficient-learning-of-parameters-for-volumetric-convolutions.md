---
layout: post
title: "Filter sharing: Efficient learning of parameters for volumetric convolutions"
date: 2016-12-08 09:35:13
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Rahul Venkataramani, Sheshadri Thiruvenkadam, Prasad Sudhakar, Hariharan Ravishankar, Vivek Vaidya
mathjax: true
---

* content
{:toc}

##### Abstract
Typical convolutional neural networks (CNNs) have several millions of parameters and require a large amount of annotated data to train them. In medical applications where training data is hard to come by, these sophisticated machine learning models are difficult to train. In this paper, we propose a method to reduce the inherent complexity of CNNs during training by exploiting the significant redundancy that is noticed in the learnt CNN filters. Our method relies on finding a small set of filters and mixing coefficients to derive every filter in each convolutional layer at the time of training itself, thereby reducing the number of parameters to be trained. We consider the problem of 3D lung nodule segmentation in CT images and demonstrate the effectiveness of our method in achieving good results with only few training examples.

##### Abstract (translated by Google)
典型的卷积神经网络（CNN）有数百万个参数，需要大量的注释数据来训练它们。在难以获得训练数据的医疗应用中，这些复杂的机器学习模型难以训练。在本文中，我们提出了一种方法，通过利用在学习CNN滤波器中注意到的重要冗余来减少CNN在训练期间的固有复杂性。我们的方法依赖于找到一小组滤波器和混合系数来在训练时在每个卷积层中导出每个滤波器，从而减少了要训练的参数的数量。我们考虑了CT图像中三维肺结节分割的问题，并证明了我们的方法在仅有少量训练样例的情况下实现良好结果的有效性。

##### URL
[https://arxiv.org/abs/1612.02575](https://arxiv.org/abs/1612.02575)

##### PDF
[https://arxiv.org/pdf/1612.02575](https://arxiv.org/pdf/1612.02575)

