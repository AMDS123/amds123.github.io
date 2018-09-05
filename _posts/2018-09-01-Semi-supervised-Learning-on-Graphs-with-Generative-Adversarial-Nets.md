---
layout: post
title: "Semi-supervised Learning on Graphs with Generative Adversarial Nets"
date: 2018-09-01 08:02:45
categories: arXiv_AI
tags: arXiv_AI Regularization Adversarial GAN
author: Ming Ding, Jie Tang, Jie Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
We investigate how generative adversarial nets (GANs) can help semi-supervised learning on graphs. We first provide insights on working principles of adversarial learning over graphs and then present GraphSGAN, a novel approach to semi-supervised learning on graphs. In GraphSGAN, generator and classifier networks play a novel competitive game. At equilibrium, generator generates fake samples in low-density areas between subgraphs. In order to discriminate fake samples from the real, classifier implicitly takes the density property of subgraph into consideration. An efficient adversarial learning algorithm has been developed to improve traditional normalized graph Laplacian regularization with a theoretical guarantee. Experimental results on several different genres of datasets show that the proposed GraphSGAN significantly outperforms several state-of-the-art methods. GraphSGAN can be also trained using mini-batch, thus enjoys the scalability advantage.

##### Abstract (translated by Google)
我们研究了生成对抗网（GAN）如何帮助图上的半监督学习。我们首先提供有关图表上对抗性学习的工作原理的见解，然后介绍GraphSGAN，这是一种在图形上进行半监督学习的新方法。在GraphSGAN中，生成器和分类器网络发挥着一种新颖的竞争游戏。在均衡时，发生器在子图之间的低密度区域生成假样本。为了区分假样本和真实样本，分类器隐含地考虑了子图的密度属性。已经开发出一种有效的对抗性学习算法来改进传统的归一化图拉普拉斯正则化，并提供理论保证。几种不同类型的数据集的实验结果表明，所提出的GraphSGAN明显优于几种最先进的方法。 GraphSGAN也可以使用小批量进行培训，因此具有可扩展性优势。

##### URL
[http://arxiv.org/abs/1809.00130](http://arxiv.org/abs/1809.00130)

##### PDF
[http://arxiv.org/pdf/1809.00130](http://arxiv.org/pdf/1809.00130)

