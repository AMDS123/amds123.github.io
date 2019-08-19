---
layout: post
title: "daBNN: A Super Fast Inference Framework for Binary Neural Networks on ARM devices"
date: 2019-08-16 06:07:57
categories: arXiv_CV
tags: arXiv_CV Inference
author: Jianhao Zhang, Yingwei Pan, Ting Yao, He Zhao, Tao Mei
mathjax: true
---

* content
{:toc}

##### Abstract
It is always well believed that Binary Neural Networks (BNNs) could drastically accelerate the inference efficiency by replacing the arithmetic operations in float-valued Deep Neural Networks (DNNs) with bit-wise operations. Nevertheless, there has not been open-source implementation in support of this idea on low-end ARM devices (e.g., mobile phones and embedded devices). In this work, we propose daBNN --- a super fast inference framework that implements BNNs on ARM devices. Several speed-up and memory refinement strategies for bit-packing, binarized convolution, and memory layout are uniquely devised to enhance inference efficiency. Compared to the recent open-source BNN inference framework, BMXNet, our daBNN is $7\times$$\sim$$23\times$ faster on a single binary convolution, and about $6\times$ faster on Bi-Real Net 18 (a BNN variant of ResNet-18). The daBNN is a BSD-licensed inference framework, and its source code, sample projects and pre-trained models are available on-line: this https URL.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.05858](https://arxiv.org/abs/1908.05858)

##### PDF
[https://arxiv.org/pdf/1908.05858](https://arxiv.org/pdf/1908.05858)

