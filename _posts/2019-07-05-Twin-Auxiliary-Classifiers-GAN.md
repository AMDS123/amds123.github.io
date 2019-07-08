---
layout: post
title: "Twin Auxiliary Classifiers GAN"
date: 2019-07-05 06:29:06
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Mingming Gong, Yanwu Xu, Chunyuan Li, Kun Zhang, Kayhan Batmanghelich
mathjax: true
---

* content
{:toc}

##### Abstract
Conditional generative models enjoy remarkable progress over the past few years. One of the popular conditional models is Auxiliary Classifier GAN (AC-GAN), which generates highly discriminative images by extending the loss function of GAN with an auxiliary classifier. However, the diversity of the generated samples by AC-GAN tends to decrease as the number of classes increases, hence limiting its power on large-scale data. In this paper, we identify the source of the low diversity issue theoretically and propose a practical solution to solve the problem. We show that the auxiliary classifier in AC-GAN imposes perfect separability, which is disadvantageous when the supports of the class distributions have significant overlap. To address the issue, we propose Twin Auxiliary Classifiers Generative Adversarial Net (TAC-GAN) that further benefits from a new player that interacts with other players (the generator and the discriminator) in GAN. Theoretically, we demonstrate that TAC-GAN can effectively minimize the divergence between the generated and real-data distributions. Extensive experimental results show that our TAC-GAN can successfully replicate the true data distributions on simulated data, and significantly improves the diversity of class-conditional image generation on real datasets.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1907.02690](https://arxiv.org/abs/1907.02690)

##### PDF
[https://arxiv.org/pdf/1907.02690](https://arxiv.org/pdf/1907.02690)

