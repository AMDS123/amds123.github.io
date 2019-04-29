---
layout: post
title: "Proximal Mean-field for Neural Network Quantization"
date: 2019-04-26 06:21:21
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Classification Gradient_Descent
author: Thalaiyasingam Ajanthan, Puneet K. Dokania, Richard Hartley, Philip H. S. Torr
mathjax: true
---

* content
{:toc}

##### Abstract
Compressing large Neural Networks (NN) by quantizing the parameters, while maintaining the performance is highly desirable due to reduced memory and time complexity. In this work, we cast NN quantization as a discrete labelling problem and leverage results from the extensively studied MRF optimization literature. Specifically, we examine relaxations to the discrete labelling problem, leading to an efficient iterative optimization procedure that involves stochastic gradient descent followed by a projection. We prove that our simple projected gradient descent approach is, in fact, equivalent to a proximal version of the well-known mean-field method. These findings allow the decades-old and theoretically grounded research on MRF optimization to be used to design better network quantization schemes. Our experiments on standard classification datasets (MNIST, CIFAR10/100, TinyImageNet) with convolutional and residual architectures evidence that our algorithm obtains fully-quantized networks with accuracies very close to the floating-point reference networks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.04353](http://arxiv.org/abs/1812.04353)

##### PDF
[http://arxiv.org/pdf/1812.04353](http://arxiv.org/pdf/1812.04353)

