---
layout: post
title: "Training Quantized Network with Auxiliary Gradient Module"
date: 2019-03-27 03:42:31
categories: arXiv_CV
tags: arXiv_CV Image_Classification Optimization Inference Classification
author: Bohan Zhuang, Lingqiao Liu, Mingkui Tan, Chunhua Shen, Ian Reid
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we seek to tackle two challenges in training low-precision networks: 1) the notorious difficulty in propagating gradient through a low-precision network due to the non-differentiable quantization function; 2) the requirement of a full-precision realization of skip connections in residual type network architectures. During training, we introduce an auxiliary gradient module which mimics the effect of skip connections to assist the optimization. We then expand the original low-precision network with the full-precision auxiliary gradient module to formulate a mixed-precision residual network and optimize it jointly with the low-precision model using weight sharing and separate batch normalization. This strategy ensures that the gradient back-propagates more easily, thus alleviating a major difficulty in training low-precision networks. Moreover, we find that when training a low-precision plain network with our method, the plain network can achieve performance similar to its counterpart with residual skip connections; i.e. the plain network without floating-point skip connections is just as effective to deploy at inference time. To further promote the gradient flow during backpropagation, we then employ a stochastic structured precision strategy to stochastically sample and quantize sub-networks while keeping other parts full-precision. We evaluate the proposed method on the image classification task over various quantization approaches and show consistent performance increases.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.11236](http://arxiv.org/abs/1903.11236)

##### PDF
[http://arxiv.org/pdf/1903.11236](http://arxiv.org/pdf/1903.11236)

