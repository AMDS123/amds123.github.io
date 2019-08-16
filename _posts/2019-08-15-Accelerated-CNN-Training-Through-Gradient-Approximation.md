---
layout: post
title: "Accelerated CNN Training Through Gradient Approximation"
date: 2019-08-15 09:11:31
categories: arXiv_CV
tags: arXiv_CV CNN Gradient_Descent
author: Ziheng Wang, Sree Harsha Nelaturu
mathjax: true
---

* content
{:toc}

##### Abstract
Training deep convolutional neural networks such as VGG and ResNet by gradient descent is an expensive exercise requiring specialized hardware such as GPUs. Recent works have examined the possibility of approximating the gradient computation while maintaining the same convergence properties. While promising, the approximations only work on relatively small datasets such as MNIST. They also fail to achieve real wall-clock speedups due to lack of efficient GPU implementations of the proposed approximation methods. In this work, we explore three alternative methods to approximate gradients, with an efficient GPU kernel implementation for one of them. We achieve wall-clock speedup with ResNet-20 and VGG-19 on the CIFAR-10 dataset upwards of 7%, with a minimal loss in validation accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.05460](http://arxiv.org/abs/1908.05460)

##### PDF
[http://arxiv.org/pdf/1908.05460](http://arxiv.org/pdf/1908.05460)

