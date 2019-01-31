---
layout: post
title: "Unsupervised Text Style Transfer using Language Models as Discriminators"
date: 2019-01-29 21:52:49
categories: arXiv_CL
tags: arXiv_CL Sentiment Adversarial GAN Style_Transfer CNN Language_Model
author: Zichao Yang, Zhiting Hu, Chris Dyer, Eric P. Xing, Taylor Berg-Kirkpatrick
mathjax: true
---

* content
{:toc}

##### Abstract
Binary classifiers are often employed as discriminators in GAN-based unsupervised style transfer systems to ensure that transferred sentences are similar to sentences in the target domain. One difficulty with this approach is that the error signal provided by the discriminator can be unstable and is sometimes insufficient to train the generator to produce fluent language. In this paper, we propose a new technique that uses a target domain language model as the discriminator, providing richer and more stable token-level feedback during the learning process. We train the generator to minimize the negative log likelihood (NLL) of generated sentences, evaluated by the language model. By using a continuous approximation of discrete sampling under the generator, our model can be trained using back-propagation in an end- to-end fashion. Moreover, our empirical results show that when using a language model as a structured discriminator, it is possible to forgo adversarial steps during training, making the process more stable. We compare our model with previous work using convolutional neural networks (CNNs) as discriminators and show that our approach leads to improved performance on three tasks: word substitution decipherment, sentiment modification, and related language translation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.11749](http://arxiv.org/abs/1805.11749)

##### PDF
[http://arxiv.org/pdf/1805.11749](http://arxiv.org/pdf/1805.11749)

