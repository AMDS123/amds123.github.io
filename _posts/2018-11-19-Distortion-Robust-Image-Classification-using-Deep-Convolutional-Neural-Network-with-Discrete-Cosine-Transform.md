---
layout: post
title: "Distortion Robust Image Classification using Deep Convolutional Neural Network with Discrete Cosine Transform"
date: 2018-11-19 11:48:11
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification
author: Md Tahmid Hossain, Shyh Wei Teng, Dengsheng Zhang, Suryani Lim, Guojun Lu
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Network is good at image classification. However, it is found to be vulnerable to image quality degradation. Even a small amount of distortion such as noise or blur can severely hamper the performance of these CNN architectures. Most of the work in the literature strives to mitigate this problem simply by fine-tuning a pre-trained CNN on mutually exclusive or a union set of distorted training data. This iterative fine-tuning process with all known types of distortion is exhaustive and the network struggles to handle unseen distortions. In this work, we propose distortion robust DCT-Net, a Discrete Cosine Transform based module integrated into a deep network which is built on top of VGG16. Unlike other works in the literature, DCT-Net is "blind" to the distortion type and level in an image both during training and testing. As a part of the training process, the proposed DCT module discards input information which mostly represents the contribution of high frequencies. The DCT-Net is trained "blindly" only once and applied in generic situation without further retraining. We also extend the idea of traditional dropout and present a training adaptive version of the same. We evaluate our proposed method against Gaussian blur, motion blur, salt and pepper noise, Gaussian noise and speckle noise added to CIFAR-10/100 and ImageNet test sets. Experimental results demonstrate that once trained, DCT-Net not only generalizes well to a variety of unseen image distortions but also outperforms other methods in the literature.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.05819](https://arxiv.org/abs/1811.05819)

##### PDF
[https://arxiv.org/pdf/1811.05819](https://arxiv.org/pdf/1811.05819)

