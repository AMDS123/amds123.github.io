---
layout: post
title: "Low-bit Quantization of Neural Networks for Efficient Inference"
date: 2019-02-18 22:28:34
categories: arXiv_CV
tags: arXiv_CV Optimization Inference
author: Yoni Choukroun, Eli Kravchik, Pavel Kisilev
mathjax: true
---

* content
{:toc}

##### Abstract
Recent breakthrough methods in machine learning make use of increasingly large deep neural networks. The gains in performance have come at the cost of a substantial increase in computation and storage, making real-time implementation on limited hardware a very challenging task. One popular approach to address this challenge is to perform low-bit precision computations via neural network quantization. However, aggressive quantization generally entails a severe penalty in terms of accuracy and usually requires the retraining of the network or resorts to higher bit precision quantization. In this paper, we formalize the linear quantization task as a Minimum Mean Squared Error (MMSE) problem for both weights and activations. This allows low-bit precision inference without the need for full network retraining. The main contributions of our approach is the optimization of the constrained MSE problem at each layer of the network, the hardware aware partitioning of the neural network parameters, and the use of multiple low precision quantized tensors for poorly approximated layers. The proposed approach allows for the first time a linear 4 bits integer precision (INT4) quantization for deployment of pretrained models on limited hardware resources.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.06822](http://arxiv.org/abs/1902.06822)

##### PDF
[http://arxiv.org/pdf/1902.06822](http://arxiv.org/pdf/1902.06822)

