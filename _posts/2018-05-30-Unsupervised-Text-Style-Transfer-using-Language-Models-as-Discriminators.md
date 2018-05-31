---
layout: post
title: "Unsupervised Text Style Transfer using Language Models as Discriminators"
date: 2018-05-30 00:02:59
categories: arXiv_CL
tags: arXiv_CL Sentiment Adversarial GAN Style_Transfer CNN Language_Model
author: Zichao Yang, Zhiting Hu, Chris Dyer, Eric P. Xing, Taylor Berg-Kirkpatrick
mathjax: true
---

* content
{:toc}

##### Abstract
Binary classifiers are often employed as discriminators in GAN-based unsupervised style transfer systems to ensure that transferred sentences are similar to sentences in the target domain. One difficulty with this approach is that the error signal provided by the discriminator can be unstable and is sometimes insufficient to train the generator to produce fluent language. In this paper, we propose a new technique that uses a target domain language model as the discriminator, providing richer and more stable token-level feedback during the learning process. We train the generator to minimize the negative log likelihood (NLL) of generated sentences, evaluated by the language model. By using a continuous approximation of discrete sampling under the generator, our model can be trained using back-propagation in an end- to-end fashion. Moreover, our empirical results show that when using a language model as a structured discriminator, it is possible to forgoe adversarial steps during training, making the process more stable. We compare our model with previous work using convolutional neural networks (CNNs) as discriminators and show that our approach leads to improved performance on three tasks: word substitution decipherment, sentiment modification, and related language translation.

##### Abstract (translated by Google)
二元分类器经常用作基于GAN的无监督式样转移系统中的鉴别器，以确保被转移的句子与目标域中的句子相似。这种方法的一个困难是鉴别器提供的错误信号可能不稳定，有时不足以训练发生器产生流畅的语言。在本文中，我们提出了一种使用目标域语言模型作为鉴别器的新技术，在学习过程中提供更丰富和更稳定的标记级反馈。我们训练生成器以最小化由语言模型评估的生成句子的负对数似然（NLL）。通过在发生器下使用离散采样的连续近似，我们的模型可以通过端到端的反向传播方式进行训练。此外，我们的实证结果表明，当使用语言模型作为结构化的鉴别器时，可以在训练期间放弃敌对步骤，使得该过程更加稳定。我们将我们的模型与先前使用卷积神经网络（CNN）作为鉴别器的工作进行了比较，并证明我们的方法可以在三项任务中提高性能：字替换解密，情感修改和相关语言翻译。

##### URL
[http://arxiv.org/abs/1805.11749](http://arxiv.org/abs/1805.11749)

##### PDF
[http://arxiv.org/pdf/1805.11749](http://arxiv.org/pdf/1805.11749)

