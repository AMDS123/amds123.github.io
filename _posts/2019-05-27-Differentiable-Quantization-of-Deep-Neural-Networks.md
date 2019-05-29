---
layout: post
title: "Differentiable Quantization of Deep Neural Networks"
date: 2019-05-27 19:03:40
categories: arXiv_CV
tags: arXiv_CV Inference Gradient_Descent
author: Stefan Uhlich, Lukas Mauch, Kazuki Yoshiyama, Fabien Cardinaux, Javier Alonso Garcia, Stephen Tiedemann, Thomas Kemp, Akira Nakamura
mathjax: true
---

* content
{:toc}

##### Abstract
We propose differentiable quantization (DQ) for efficient deep neural network (DNN) inference where gradient descent is used to learn the quantizer's step size, dynamic range and bitwidth. Training with differentiable quantizers brings two main benefits: first, DQ does not introduce hyperparameters; second, we can learn for each layer a different step size, dynamic range and bitwidth. Our experiments show that DNNs with heterogeneous and learned bitwidth yield better performance than DNNs with a homogeneous one. Further, we show that there is one natural DQ parametrization especially well suited for training. We confirm our findings with experiments on CIFAR-10 and ImageNet and we obtain quantized DNNs with learned quantization parameters achieving state-of-the-art performance.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.11452](https://arxiv.org/abs/1905.11452)

##### PDF
[https://arxiv.org/pdf/1905.11452](https://arxiv.org/pdf/1905.11452)

