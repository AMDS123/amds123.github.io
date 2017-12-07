---
layout: post
title: "Convolutional Networks with Adaptive Computation Graphs"
date: 2017-11-30 16:45:25
categories: arXiv_CV
tags: arXiv_CV Adversarial CNN
author: Andreas Veit, Serge Belongie
mathjax: true
---

* content
{:toc}

##### Abstract
Do convolutional networks really need a fixed feed-forward structure? Often, a neural network is already confident after a few layers about the high-level concept shown in the image. However, due to the fixed network structure, all remaining layers still need to be evaluated. What if the network could jump right to a layer that is specialized in fine-grained differences of the image's content? In this work, we propose Adanets, a family of convolutional networks with adaptive computation graphs. Following a high-level structure similar to residual networks (Resnets), the key difference is that for each layer a gating function determines whether to execute the layer or move on to the next one. In experiments on CIFAR-10 and ImageNet we demonstrate that Adanets efficiently allocate computational budget among layers and learn distinct layers specializing in similar categories. Adanet 50 achieves a top 5 error rate of 7.94% on ImageNet using 30% fewer computations than Resnet 34, which only achieves 8.58%. Lastly, we study the effect of adaptive computation graphs on the susceptibility towards adversarial examples. We observe that Adanets show a higher robustness towards adversarial attacks, complementing other defenses such as JPEG compression.

##### Abstract (translated by Google)
卷积网络是否真的需要一个固定的前馈结构？经过几层关于图像中显示的高级概念之后，神经网络已经很自信了。但是，由于网络结构的固定，所有剩余的层仍然需要评估。如果网络能够跳到一个专门针对图像内容的细微差别的图层，该怎么办？在这项工作中，我们提出了具有自适应计算图的卷积网络Adanets。遵循与残余网络（Resnets）类似的高层结构，关键的区别在于，对于每一层，门控功能决定是执行该层还是转到下一层。在CIFAR-10和ImageNet的实验中，我们证明了Adanets有效地分配层间的计算预算，并学习专门从事类似类的不同层。 Adanet 50在ImageNet上实现了7.94％的前5个错误率，比Resnet 34少了30％，而Resnet 34只能达到8.58％。最后，我们研究自适应计算图对对抗实例的易感性的影响。我们观察到Adanets显示出更强大的对抗攻击能力，补充了JPEG压缩等其他防御措施。

##### URL
[https://arxiv.org/abs/1711.11503](https://arxiv.org/abs/1711.11503)

##### PDF
[https://arxiv.org/pdf/1711.11503](https://arxiv.org/pdf/1711.11503)

