---
layout: post
title: "AdaBatch: Adaptive Batch Sizes for Training Deep Neural Networks"
date: 2017-12-06 04:19:14
categories: arXiv_CV
tags: arXiv_CV Gradient_Descent
author: Aditya Devarakonda, Maxim Naumov, Michael Garland
mathjax: true
---

* content
{:toc}

##### Abstract
Training deep neural networks with Stochastic Gradient Descent, or its variants, requires careful choice of both learning rate and batch size. While smaller batch sizes generally converge in fewer training epochs, larger batch sizes offer more parallelism and hence better computational efficiency. We have developed a new training approach that, rather than statically choosing a single batch size for all epochs, adaptively increases the batch size during the training process. Our method delivers the convergence rate of small batch sizes while achieving performance similar to large batch sizes. We analyse our approach using the standard AlexNet, ResNet, and VGG networks operating on the popular CIFAR-10, CIFAR-100, and ImageNet datasets. Our results demonstrate that learning with adaptive batch sizes can improve performance by factors of up to 6.25 on 4 NVIDIA Tesla P100 GPUs while changing accuracy by less than 1% relative to training with fixed batch sizes.

##### Abstract (translated by Google)
使用Stochastic Gradient Descent或其变体训练深度神经网络需要仔细选择学习速率和批次大小。虽然较小的批量通常在较少的训练时期收敛，但较大的批量提供了更多的并行性，并因此提高了计算效率。我们开发了一种新的培训方法，而不是为所有时期静态地选择一个批量规模，而是在培训过程中自适应地增加批量规模。我们的方法提供小批量的收敛率，同时达到与大批量相似的性能。我们使用在流行的CIFAR-10，CIFAR-100和ImageNet数据集上运行的标准AlexNet，ResNet和VGG网络来分析我们的方法。我们的研究结果表明，使用自适应批处理大小进行学习，可以在4个NVIDIA Tesla P100 GPU上以6.25倍的系数提高性能，同时相对于使用固定批处理大小的培训，精度可以提高不到1％。

##### URL
[http://arxiv.org/abs/1712.02029](http://arxiv.org/abs/1712.02029)

##### PDF
[http://arxiv.org/pdf/1712.02029](http://arxiv.org/pdf/1712.02029)

