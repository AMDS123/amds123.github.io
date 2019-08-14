---
layout: post
title: "Effective Training of Convolutional Neural Networks with Low-bitwidth Weights and Activations"
date: 2019-08-10 11:48:55
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN
author: Bohan Zhuang, Jing Liu, Mingkui Tan, Lingqiao Liu, Ian Reid, Chunhua Shen
mathjax: true
---

* content
{:toc}

##### Abstract
This paper tackles the problem of training a deep convolutional neural network of both low-bitwidth weights and activations. Optimizing a low-precision network is very challenging due to the non-differentiability of the quantizer, which may result in substantial accuracy loss. To address this, we propose three practical approaches, including (i) progressive quantization; (ii) stochastic precision; and (iii) joint knowledge distillation to improve the network training. First, for progressive quantization, we propose two schemes to progressively find good local minima. Specifically, we propose to first optimize a net with quantized weights and subsequently quantize activations. This is in contrast to the traditional methods which optimize them simultaneously. Furthermore, we propose a second progressive quantization scheme which gradually decreases the bit-width from high-precision to low-precision during training. Second, to alleviate the excessive training burden due to the multi-round training stages, we further propose a one-stage stochastic precision strategy to randomly sample and quantize sub-networks while keeping other parts in full-precision. Finally, we adopt a novel learning scheme to jointly train a full-precision model alongside the low-precision one. By doing so, the full-precision model provides hints to guide the low-precision model training and significantly improves the performance of the low-precision network. Extensive experiments on various datasets (e.g., CIFAR-100, ImageNet) show the effectiveness of the proposed methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.04680](http://arxiv.org/abs/1908.04680)

##### PDF
[http://arxiv.org/pdf/1908.04680](http://arxiv.org/pdf/1908.04680)

