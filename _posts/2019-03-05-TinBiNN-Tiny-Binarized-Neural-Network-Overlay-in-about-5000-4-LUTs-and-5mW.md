---
layout: post
title: "TinBiNN: Tiny Binarized Neural Network Overlay in about 5,000 4-LUTs and 5mW"
date: 2019-03-05 14:51:36
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Inference Detection
author: Guy G.F. Lemieux, Joe Edwards, Joel Vandergriendt, Aaron Severance, Ryan De Iaco, Abdullah Raouf, Hussein Osman, Tom Watzka, Satwant Singh
mathjax: true
---

* content
{:toc}

##### Abstract
Reduced-precision arithmetic improves the size, cost, power and performance of neural networks in digital logic. In convolutional neural networks, the use of 1b weights can achieve state-of-the-art error rates while eliminating multiplication, reducing storage and improving power efficiency. The BinaryConnect binary-weighted system, for example, achieves 9.9% error using floating-point activations on the CIFAR-10 dataset. In this paper, we introduce TinBiNN, a lightweight vector processor overlay for accelerating inference computations with 1b weights and 8b activations. The overlay is very small -- it uses about 5,000 4-input LUTs and fits into a low cost iCE40 UltraPlus FPGA from Lattice Semiconductor. To show this can be useful, we build two embedded 'person detector' systems by shrinking the original BinaryConnect network. The first is a 10-category classifier with a 89% smaller network that runs in 1,315ms and achieves 13.6% error. The other is a 1-category classifier that is even smaller, runs in 195ms, and has only 0.4% error. In both classifiers, the error can be attributed entirely to training and not reduced precision.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.06630](http://arxiv.org/abs/1903.06630)

##### PDF
[http://arxiv.org/pdf/1903.06630](http://arxiv.org/pdf/1903.06630)

