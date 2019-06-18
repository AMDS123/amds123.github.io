---
layout: post
title: "EnlightenGAN: Deep Light Enhancement without Paired Supervision"
date: 2019-06-17 11:54:20
categories: arXiv_CV
tags: arXiv_CV Adversarial Attention GAN Image_Enhancement Deep_Learning
author: Yifan Jiang, Xinyu Gong, Ding Liu, Yu Cheng, Chen Fang, Xiaohui Shen, Jianchao Yang, Pan Zhou, Zhangyang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning-based methods have achieved remarkable success in image restoration and enhancement, but are they still competitive when there is a lack of paired training data? As one such example, this paper explores the low-light image enhancement problem, where in practice it is extremely challenging to simultaneously take a low-light and a normal-light photo of the same visual scene. We propose a highly effective unsupervised generative adversarial network, dubbed EnlightenGAN, that can be trained without low/normal-light image pairs, yet proves to generalize very well on various real-world test images. Instead of supervising the learning using ground truth data, we propose to regularize the unpaired training using the information extracted from the input itself, and benchmark a series of innovations for the low-light image enhancement problem, including a global-local discriminator structure, a self-regularized perceptual loss fusion, and attention mechanism. Through extensive experiments, our proposed approach outperforms recent methods under a variety of metrics in terms of visual quality and subjective user study. Thanks to the great flexibility brought by unpaired training, EnlightenGAN is demonstrated to be easily adaptable to enhancing real-world images from various domains. The code is available at \url{https://github.com/yueruchen/EnlightenGAN}

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.06972](http://arxiv.org/abs/1906.06972)

##### PDF
[http://arxiv.org/pdf/1906.06972](http://arxiv.org/pdf/1906.06972)

