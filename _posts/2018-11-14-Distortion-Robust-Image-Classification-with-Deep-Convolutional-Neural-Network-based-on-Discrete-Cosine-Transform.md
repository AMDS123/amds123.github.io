---
layout: post
title: "Distortion Robust Image Classification with Deep Convolutional Neural Network based on Discrete Cosine Transform"
date: 2018-11-14 14:52:06
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification
author: Md Tahmid Hossain, Shyh Wei Teng, Dengsheng Zhang, Suryani Lim, Guojun Lu
mathjax: true
---

* content
{:toc}

##### Abstract
State of the art CNN models for image classification are found to be highly vulnerable to image quality degradation. It is observed that even a small amount of distortion introduced in an image in the form of noise or blur severely hampers the performance of these CNN architectures. Most of the work in the literature strive to mitigate this problem simply by fine-tuning a pre-trained model on mutually exclusive or union set of distorted training data. This iterative fine-tuning process with all possible types of distortion is exhaustive and struggles to handle unseen distortions. In this work, we propose DCT-Net, a Discrete Cosine Transform based module integrated into a deep network which is built on top of VGG16 \cite{vgg1}. The proposed DCT module operates during training and discards input information based on DCT coefficients which represent the contribution of sampling frequencies. We show that this approach enables the network to be trained at one go without having to generate training data with different type of expected distortions. We also extend the idea of traditional dropout and present a training adaptive version of the same. During tests, we introduce Gaussian blur, motion blur, salt and pepper noise, Gaussian white noise and speckle noise to CIFAR10, CIFAR-100 \cite{cifar1} and ImageNet \cite{imagenet1} dataset. We evaluate our deep network on these benchmark databases and show that it not only generalizes well to a variety of image distortions but also outperforms sate-of-the-art.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.05819](http://arxiv.org/abs/1811.05819)

##### PDF
[http://arxiv.org/pdf/1811.05819](http://arxiv.org/pdf/1811.05819)

