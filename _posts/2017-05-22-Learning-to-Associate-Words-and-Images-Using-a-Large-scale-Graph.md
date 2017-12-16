---
layout: post
title: "Learning to Associate Words and Images Using a Large-scale Graph"
date: 2017-05-22 14:24:08
categories: arXiv_CV
tags: arXiv_CV CNN
author: Heqing Ya, Haonan Sun, Jeffrey Helt, Tai Sing Lee
mathjax: true
---

* content
{:toc}

##### Abstract
We develop an approach for unsupervised learning of associations between co-occurring perceptual events using a large graph. We applied this approach to successfully solve the image captcha of China's railroad system. The approach is based on the principle of suspicious coincidence. In this particular problem, a user is presented with a deformed picture of a Chinese phrase and eight low-resolution images. They must quickly select the relevant images in order to purchase their train tickets. This problem presents several challenges: (1) the teaching labels for both the Chinese phrases and the images were not available for supervised learning, (2) no pre-trained deep convolutional neural networks are available for recognizing these Chinese phrases or the presented images, and (3) each captcha must be solved within a few seconds. We collected 2.6 million captchas, with 2.6 million deformed Chinese phrases and over 21 million images. From these data, we constructed an association graph, composed of over 6 million vertices, and linked these vertices based on co-occurrence information and feature similarity between pairs of images. We then trained a deep convolutional neural network to learn a projection of the Chinese phrases onto a 230-dimensional latent space. Using label propagation, we computed the likelihood of each of the eight images conditioned on the latent space projection of the deformed phrase for each captcha. The resulting system solved captchas with 77% accuracy in 2 seconds on average. Our work, in answering this practical challenge, illustrates the power of this class of unsupervised association learning techniques, which may be related to the brain's general strategy for associating language stimuli with visual objects on the principle of suspicious coincidence.

##### Abstract (translated by Google)
我们开发了一种方法来使用大图来对共现感知事件之间的关联进行无监督学习。我们应用这种方法成功地解决了中国铁路系统的图像验证问题。这种做法是基于可疑巧合的原则。在这个特定的问题中，用户被呈现有中文短语的变形图片和八个低分辨率图像。他们必须快速选择相关的图像，以购买他们的火车票。这个问题提出了几个挑战：（1）中文短语和图像的教学标签不能用于监督学习，（2）没有预先训练的深度卷积神经网络可用于识别这些中文短语或所呈现的图像， （3）每个验证码必须在几秒钟内解决。我们收集了260万个验证码，260万个变形的中文短语和2100多万张图片。从这些数据中，我们构造了一个由600多万个顶点组成的关联图，并且根据图像对之间的共现信息和特征相似度来链接这些顶点。然后，我们训练了深度卷积神经网络来学习中文短语在230维空间的投影。使用标签传播，我们计算了八个图像中的每一个的可能性，这些图像以每个验证码的变形短语的潜在空间投影为条件。所得到的系统平均在2秒内解决了验证码77％的准确性。我们的工作在回答这个实际的挑战时，说明了这种无监督关联学习技术的力量，这可能与大脑根据可疑巧合的原则将语言刺激与视觉对象联系起来的一般策略有关。

##### URL
[https://arxiv.org/abs/1705.07768](https://arxiv.org/abs/1705.07768)

##### PDF
[https://arxiv.org/pdf/1705.07768](https://arxiv.org/pdf/1705.07768)

