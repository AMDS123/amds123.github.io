---
layout: post
title: "Mixed Precision Quantization of ConvNets via Differentiable Neural Architecture Search"
date: 2018-11-30 23:15:45
categories: arXiv_CV
tags: arXiv_CV Optimization Inference
author: Bichen Wu, Yanghan Wang, Peizhao Zhang, Yuandong Tian, Peter Vajda, Kurt Keutzer
mathjax: true
---

* content
{:toc}

##### Abstract
Recent work in network quantization has substantially reduced the time and space complexity of neural network inference, enabling their deployment on embedded and mobile devices with limited computational and memory resources. However, existing quantization methods often represent all weights and activations with the same precision (bit-width). In this paper, we explore a new dimension of the design space: quantizing different layers with different bit-widths. We formulate this problem as a neural architecture search problem and propose a novel differentiable neural architecture search (DNAS) framework to efficiently explore its exponential search space with gradient-based optimization. Experiments show we surpass the state-of-the-art compression of ResNet on CIFAR-10 and ImageNet. Our quantized models with 21.1x smaller model size or 103.9x lower computational cost can still outperform baseline quantized or even full precision models.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.00090](http://arxiv.org/abs/1812.00090)

##### PDF
[http://arxiv.org/pdf/1812.00090](http://arxiv.org/pdf/1812.00090)

