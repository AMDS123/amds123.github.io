---
layout: post
title: "Accurate deep neural network inference using computational phase-change memory"
date: 2019-06-07 14:50:52
categories: arXiv_CV
tags: arXiv_CV GAN CNN Inference Classification Deep_Learning
author: Vinay Joshi, Manuel Le Gallo, Irem Boybat, Simon Haefeli, Christophe Piveteau, Martino Dazzi, Bipin Rajendran, Abu Sebastian, Evangelos Eleftheriou
mathjax: true
---

* content
{:toc}

##### Abstract
In-memory computing is a promising non-von Neumann approach where certain computational tasks are performed within memory units by exploiting the physical attributes of memory devices. For instance, crossbar arrays of resistive memory devices can be used to store a matrix and perform analog matrix-vector multiplications at constant O(1) time complexity without intermediate movements of data. This functionality is very appealing for making energy-efficient deep learning inference hardware, where the weights of the neural network layers would be encoded in such crossbar arrays. However, due to device variability and noise, the network needs to be trained in a specific way so that transferring the digitally trained weights to the analog resistive memory devices will not result in appreciable loss of accuracy. Here, we introduce a methodology to train ResNet-type convolutional neural networks that results in almost no accuracy loss when transferring weights to analog in-memory computing hardware based on phase-change memory (PCM). Our experimental results demonstrate an as-programmed classification accuracy of 93.69% on the CIFAR-10 dataset with ResNet-32, which stays above 92.6% over a one day period, where each of the 361,722 synaptic weights of the network is programmed on just two PCM devices organized in a differential configuration.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1906.03138](https://arxiv.org/abs/1906.03138)

##### PDF
[https://arxiv.org/pdf/1906.03138](https://arxiv.org/pdf/1906.03138)

