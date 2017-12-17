---
layout: post
title: "Extremely Large Minibatch SGD: Training ResNet-50 on ImageNet in 15 Minutes"
date: 2017-11-12 17:36:46
categories: arXiv_CV
tags: arXiv_CV
author: Takuya Akiba, Shuji Suzuki, Keisuke Fukuda
mathjax: true
---

* content
{:toc}

##### Abstract
We demonstrate that training ResNet-50 on ImageNet for 90 epochs can be achieved in 15 minutes with 1024 Tesla P100 GPUs. This was made possible by using a large minibatch size of 32k. To maintain accuracy with this large minibatch size, we employed several techniques such as RMSprop warm-up, batch normalization without moving averages, and a slow-start learning rate schedule. This paper also describes the details of the hardware and software of the system used to achieve the above performance.

##### Abstract (translated by Google)
我们证明在90分钟的ImageNet上培训ResNet-50可以在1024分钟的Tesla P100 GPU中15分钟内完成。这是通过使用32k的大型小批量大小而成为可能的。为了保持这个大的小批量大小的准确性，我们采用了一些技术，如RMSprop预热，不移动平均值的批量归一化，以及慢启动学习率计划。本文还介绍了用于实现上述性能的系统的硬件和软件的细节。

##### URL
[https://arxiv.org/abs/1711.04325](https://arxiv.org/abs/1711.04325)

##### PDF
[https://arxiv.org/pdf/1711.04325](https://arxiv.org/pdf/1711.04325)

