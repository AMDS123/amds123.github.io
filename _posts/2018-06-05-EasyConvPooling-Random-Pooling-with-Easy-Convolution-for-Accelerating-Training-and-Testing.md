---
layout: post
title: "EasyConvPooling: Random Pooling with Easy Convolution for Accelerating Training and Testing"
date: 2018-06-05 14:56:10
categories: arXiv_CV
tags: arXiv_CV CNN
author: Jianzhong Sheng, Chuanbo Chen, Chenchen Fu, Chun Jason Xue
mathjax: true
---

* content
{:toc}

##### Abstract
Convolution operations dominate the overall execution time of Convolutional Neural Networks (CNNs). This paper proposes an easy yet efficient technique for both Convolutional Neural Network training and testing. The conventional convolution and pooling operations are replaced by Easy Convolution and Random Pooling (ECP). In ECP, we randomly select one pixel out of four and only conduct convolution operations of the selected pixel. As a result, only a quarter of the conventional convolution computations are needed. Experiments demonstrate that the proposed EasyConvPooling can achieve 1.45x speedup on training time and 1.64x on testing time. What's more, a speedup of 5.09x on pure Easy Convolution operations is obtained compared to conventional convolution operations.

##### Abstract (translated by Google)
卷积运算主导着卷积神经网络（CNN）的整体执行时间。本文提出了一种简单而有效的卷积神经网络训练和测试技术。传统的卷积和池化操作被简易卷积和随机池（ECP）所取代。在ECP中，我们从四个中随机选择一个像素，并仅对所选像素进行卷积运算。结果，只需要传统卷积计算的四分之一。实验表明，EasyConvPooling的训练时间可以达到1.45倍，测试时间达到1.64倍。更重要的是，与传统的卷积运算相比，纯粹的Easy Convolution运算获得了5.09倍的加速比。

##### URL
[http://arxiv.org/abs/1806.01729](http://arxiv.org/abs/1806.01729)

##### PDF
[http://arxiv.org/pdf/1806.01729](http://arxiv.org/pdf/1806.01729)

