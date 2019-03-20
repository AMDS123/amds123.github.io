---
layout: post
title: "Trained Uniform Quantization for Accurate and Efficient Neural Network Inference on Fixed-Point Hardware"
date: 2019-03-19 15:50:24
categories: arXiv_CV
tags: arXiv_CV Inference Classification Gradient_Descent
author: Sambhav R. Jain, Albert Gural, Michael Wu, Chris Dick
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a method of training quantization clipping thresholds for uniform symmetric quantizers using standard backpropagation and gradient descent. Our quantizers are constrained to use power-of-2 scale-factors and per-tensor scaling for weights and activations. These constraints make our methods better suited for hardware implementations. Training with these difficult constraints is enabled by a combination of three techniques: using accurate threshold gradients to achieve range-precision trade-off, training thresholds in log-domain, and training with an adaptive gradient optimizer. We refer to this collection of techniques as Adaptive-Gradient Log-domain Threshold Training (ALT). We present analytical support for the general robustness of our methods and empirically validate them on various CNNs for ImageNet classification. We are able to achieve floating-point or near-floating-point accuracy on traditionally difficult networks such as MobileNets in less than 5 epochs of quantized (8-bit) retraining. Finally, we present Graffitist, a framework that enables immediate quantization of TensorFlow graphs using our methods. Code available at https://github.com/Xilinx/graffitist .

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.08066](http://arxiv.org/abs/1903.08066)

##### PDF
[http://arxiv.org/pdf/1903.08066](http://arxiv.org/pdf/1903.08066)

