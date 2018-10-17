---
layout: post
title: "DN-ResNet: Efficient Deep Residual Network for Image Denoising"
date: 2018-10-16 00:33:09
categories: arXiv_CV
tags: arXiv_CV Knowledge Image_Enhancement CNN Deep_Learning
author: Haoyu Ren, Mostafa El-Khamy, Jungwon Lee
mathjax: true
---

* content
{:toc}

##### Abstract
A deep learning approach to blind denoising of images without complete knowledge of the noise statistics is considered. We propose DN-ResNet, which is a deep convolutional neural network (CNN) consisting of several residual blocks (ResBlocks). With cascade training, DN-ResNet is more accurate and more computationally efficient than the state of art denoising networks. An edge-aware loss function is further utilized in training DN-ResNet, so that the denoising results have better perceptive quality compared to conventional loss function. Next, we introduce the depthwise separable DN-ResNet (DS-DN-ResNet) utilizing the proposed Depthwise Seperable ResBlock (DS-ResBlock) instead of standard ResBlock, which has much less computational cost. DS-DN-ResNet is incrementally evolved by replacing the ResBlocks in DN-ResNet by DS-ResBlocks stage by stage. As a result, high accuracy and good computational efficiency are achieved concurrently. Whereas previous state of art deep learning methods focused on denoising either Gaussian or Poisson corrupted images, we consider denoising images having the more practical Poisson with additive Gaussian noise as well. The results show that DN-ResNets are more efficient, robust, and perform better denoising than current state of art deep learning methods, as well as the popular variants of the BM3D algorithm, in cases of blind and non-blind denoising of images corrupted with Poisson, Gaussian or Poisson-Gaussian noise. Our network also works well for other image enhancement task such as compressed image restoration.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.06766](http://arxiv.org/abs/1810.06766)

##### PDF
[http://arxiv.org/pdf/1810.06766](http://arxiv.org/pdf/1810.06766)

