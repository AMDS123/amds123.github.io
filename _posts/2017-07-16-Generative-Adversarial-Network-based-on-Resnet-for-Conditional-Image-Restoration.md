---
layout: post
title: "Generative Adversarial Network based on Resnet for Conditional Image Restoration"
date: 2017-07-16 13:38:36
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Meng Wang, Huafeng Li, Fang Li
mathjax: true
---

* content
{:toc}

##### Abstract
The GANs promote an adversarive game to approximate complex and jointed example probability. The networks driven by noise generate fake examples to approximate realistic data distributions. Later the conditional GAN merges prior-conditions as input in order to transfer attribute vectors to the corresponding data. However, the CGAN is not designed to deal with the high dimension conditions since indirect guide of the learning is inefficiency. In this paper, we proposed a network ResGAN to generate fine images in terms of extremely degenerated images. The coarse images aligned to attributes are embedded as the generator inputs and classifier labels. In generative network, a straight path similar to the Resnet is cohered to directly transfer the coarse images to the higher layers. And adversarial training is circularly implemented to prevent degeneration of the generated images. Experimental results of applying the ResGAN to datasets MNIST, CIFAR10/100 and CELEBA show its higher accuracy to the state-of-art GANs.

##### Abstract (translated by Google)
GANs推广一个敌对的游戏来逼近复杂的和联合的例子概率。由噪声驱动的网络产生假实例来逼近实际的数据分布。之后，条件GAN将先验条件合并为输入，以便将属性向量转移到相应的数据。然而，由于学习的间接指导是无效的，所以CGAN并不是为了处理高维情况而设计的。在本文中，我们提出了一个网络ResGAN来生成极其退化的图像方面的精细图像。与属性对齐的粗糙图像被嵌入为发生器输入和分类器标签。在生成网络中，类似于Resnet的直线路径被凝聚以直接将粗糙图像传送到更高层。对抗训练是循环执行的，以防止生成图像的退化。将ResGAN应用于数据集MNIST，CIFAR10 / 100和CELEBA的实验结果表明其对于现有技术的GAN具有更高的准确性。

##### URL
[https://arxiv.org/abs/1707.04881](https://arxiv.org/abs/1707.04881)

##### PDF
[https://arxiv.org/pdf/1707.04881](https://arxiv.org/pdf/1707.04881)

