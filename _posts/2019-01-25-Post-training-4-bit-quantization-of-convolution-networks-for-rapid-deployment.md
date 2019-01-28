---
layout: post
title: "Post-training 4-bit quantization of convolution networks for rapid-deployment"
date: 2019-01-25 07:23:56
categories: arXiv_CV
tags: arXiv_CV CNN
author: Ron Banner, Yury Nahshan, Elad Hoffer, Daniel Soudry
mathjax: true
---

* content
{:toc}

##### Abstract
Neural network quantization has significant benefits for deployment on dedicated accelerators. We introduce the first practical 4-bit post training quantization approach: it does not involve training the quantized model ("fine-tuning"), nor it requires the availability of the full dataset. Yet, it maintains accuracy that is just a few percents less the state-of-the-art baseline across a wide range of convolutional models. This is unlike traditional approaches that fail entirely in these settings. To achieve this, we convert a full precision pre-trained network to a limited precision network by minimizing the quantization error at the tensor level. We analyze the trade-off between quantization noise and clipping distortion in low precision networks. This enables us to derive approximate analytical expressions for the mean-square-error degradation due to clipping. By optimizing these expressions, we show marked improvements over standard quantization schemes that normally avoid clipping.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.05723](http://arxiv.org/abs/1810.05723)

##### PDF
[http://arxiv.org/pdf/1810.05723](http://arxiv.org/pdf/1810.05723)

