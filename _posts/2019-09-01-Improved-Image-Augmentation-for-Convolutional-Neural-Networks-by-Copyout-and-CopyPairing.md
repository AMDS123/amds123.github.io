---
layout: post
title: "Improved Image Augmentation for Convolutional Neural Networks by Copyout and CopyPairing"
date: 2019-09-01 12:59:09
categories: arXiv_CV
tags: arXiv_CV CNN
author: Philip May
mathjax: true
---

* content
{:toc}

##### Abstract
Image augmentation is a widely used technique to improve the performance of convolutional neural networks (CNNs). In common image shifting, cropping, flipping, shearing and rotating are used for augmentation. But there are more advanced techniques like Cutout and SamplePairing. In this work we present two improvements of the state-of-the-art Cutout and SamplePairing techniques. Our new method called Copyout takes a square patch of another random training image and copies it onto a random location of each image used for training. The second technique we discovered is called CopyPairing. It combines Copyout and SamplePairing for further augmentation and even better performance. We apply different experiments with these augmentation techniques on the CIFAR-10 dataset to evaluate and compare them under different configurations. In our experiments we show that Copyout reduces the test error rate by 8.18% compared with Cutout and 4.27% compared with SamplePairing. CopyPairing reduces the test error rate by 11.97% compared with Cutout and 8.21% compared with SamplePairing.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.00390](http://arxiv.org/abs/1909.00390)

##### PDF
[http://arxiv.org/pdf/1909.00390](http://arxiv.org/pdf/1909.00390)

