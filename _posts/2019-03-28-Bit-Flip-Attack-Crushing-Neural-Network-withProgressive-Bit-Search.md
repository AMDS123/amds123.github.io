---
layout: post
title: "Bit-Flip Attack: Crushing Neural Network withProgressive Bit Search"
date: 2019-03-28 21:07:48
categories: arXiv_CV
tags: arXiv_CV Adversarial
author: Adnan Siraj Rakin, Zhezhi He, Deliang Fan
mathjax: true
---

* content
{:toc}

##### Abstract
Several important security issues of Deep Neural Network (DNN) have been raised recently associated with different applications and components. The most widely investigated security concern of DNN is from its malicious input, a.k.a adversarial example. Nevertheless, the security challenge of DNN's parameters is not well explored yet. In this work, we are the first to propose a novel DNN weight attack methodology called Bit-Flip Attack (BFA) which can crush a neural network through maliciously flipping extremely small amount of bits within its weight storage memory system (i.e., DRAM). The bit-flip operations could be conducted through well-known Row-Hammer attack, while our main contribution is to develop an algorithm to identify the most vulnerable bits of DNN weight parameters (stored in memory as binary bits), that could maximize the accuracy degradation with a minimum number of bit-flips. Our proposed BFA utilizes a Progressive Bit Search (PBS) method which combines gradient ranking and progressive search to identify the most vulnerable bit to be flipped. With the aid of PBS, we can successfully attack a ResNet-18 fully malfunction (i.e., top-1 accuracy degrade from 69.8% to 0.1%) only through 13 bit-flips out of 93 million bits, while randomly flipping 100 bits merely degrades the accuracy by less than 1%.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.12269](http://arxiv.org/abs/1903.12269)

##### PDF
[http://arxiv.org/pdf/1903.12269](http://arxiv.org/pdf/1903.12269)

