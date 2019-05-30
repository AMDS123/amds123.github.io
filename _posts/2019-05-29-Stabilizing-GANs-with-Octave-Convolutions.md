---
layout: post
title: "Stabilizing GANs with Octave Convolutions"
date: 2019-05-29 15:28:54
categories: arXiv_CV
tags: arXiv_CV GAN CNN
author: Ricard Durall, Franz-Josef Pfreundt, Janis Keuper
mathjax: true
---

* content
{:toc}

##### Abstract
In this preliminary report, we present a simple but very effective technique to stabilize the training of CNN based GANs. Motivated by recently published methods using frequency decomposition of convolutions (e.g. Octave Convolutions), we propose a novel convolution scheme to stabilize the training and reduce the likelihood of a mode collapse. The basic idea of our approach is to split convolutional filters into additive high and low frequency parts, while shifting weight updates from low to high during the training. Intuitively, this method forces GANs to learn low frequency coarse image structures before descending into fine (high frequency) details. Our approach is orthogonal and complementary to existing stabilization methods and can simply plugged into any CNN based GAN architecture. First experiments on the CelebA dataset show the effectiveness of the proposed method.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.12534](http://arxiv.org/abs/1905.12534)

##### PDF
[http://arxiv.org/pdf/1905.12534](http://arxiv.org/pdf/1905.12534)

