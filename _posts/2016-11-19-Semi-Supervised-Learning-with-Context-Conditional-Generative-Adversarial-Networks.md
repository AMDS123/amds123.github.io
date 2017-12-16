---
layout: post
title: "Semi-Supervised Learning with Context-Conditional Generative Adversarial Networks"
date: 2016-11-19 21:02:14
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Emily Denton, Sam Gross, Rob Fergus
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a simple semi-supervised learning approach for images based on in-painting using an adversarial loss. Images with random patches removed are presented to a generator whose task is to fill in the hole, based on the surrounding pixels. The in-painted images are then presented to a discriminator network that judges if they are real (unaltered training images) or not. This task acts as a regularizer for standard supervised training of the discriminator. Using our approach we are able to directly train large VGG-style networks in a semi-supervised fashion. We evaluate on STL-10 and PASCAL datasets, where our approach obtains performance comparable or superior to existing methods.

##### Abstract (translated by Google)
我们介绍一个简单的半监督学习方法的基础上使用敌对损失在绘画图像。随机补丁被移除的图像被呈现给其任务是根据周围像素填充洞的发生器。然后将内嵌的图像呈现给鉴别器网络，该网络判断它们是否是真实的（未改变的训练图像）。这个任务作为鉴别者的标准监督训练的正规化者。使用我们的方法，我们能够以半监督的方式直接训练大型VGG风格的网络。我们评估STL-10和PASCAL数据集，其中我们的方法获得的性能可与现有方法相媲美或优于现有方法。

##### URL
[https://arxiv.org/abs/1611.06430](https://arxiv.org/abs/1611.06430)

##### PDF
[https://arxiv.org/pdf/1611.06430](https://arxiv.org/pdf/1611.06430)

