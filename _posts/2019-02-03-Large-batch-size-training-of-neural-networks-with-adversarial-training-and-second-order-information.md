---
layout: post
title: "Large batch size training of neural networks with adversarial training and second-order information"
date: 2019-02-03 20:56:27
categories: arXiv_AI
tags: arXiv_AI Adversarial Gradient_Descent
author: Zhewei Yao, Amir Gholami, Kurt Keutzer, Michael Mahoney
mathjax: true
---

* content
{:toc}

##### Abstract
The most straightforward method to accelerate Stochastic Gradient Descent (SGD) is to distribute the randomly selected batch of inputs over multiple processors. To keep the distributed processors fully utilized requires commensurately growing the batch size; however, large batch training usually leads to poor generalization. Existing solutions for large batch training either significantly degrade accuracy or require massive hyper-parameter tuning. To address this issue, we propose a novel large batch training method which combines recent results in adversarial training and second order information. We extensively evaluate our method on Cifar-10/100, SVHN, TinyImageNet, and ImageNet datasets, using multiple NNs, including residual networks as well as smaller networks such as SqueezeNext. Our new approach exceeds the performance of the existing solutions in terms of both accuracy and the number of SGD iterations (up to 1\% and $5\times$, respectively). We emphasize that this is achieved without any additional hyper-parameter tuning to tailor our proposed method in any of these experiments. With slight hyper-parameter tuning, our method can reduce the number of SGD iterations of ResNet18 on Cifar-10/ImageNet to $44.8\times$ and $28.8\times$, respectively. We have open sourced the method including tools for computing Hessian spectrum.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.01021](http://arxiv.org/abs/1810.01021)

##### PDF
[http://arxiv.org/pdf/1810.01021](http://arxiv.org/pdf/1810.01021)

