---
layout: post
title: "Fast-converging Conditional Generative Adversarial Networks for Image Synthesis"
date: 2018-05-05 00:18:19
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Classification
author: Chengcheng Li, Zi Wang, Hairong Qi
mathjax: true
---

* content
{:toc}

##### Abstract
Building on top of the success of generative adversarial networks (GANs), conditional GANs attempt to better direct the data generation process by conditioning with certain additional information. Inspired by the most recent AC-GAN, in this paper we propose a fast-converging conditional GAN (FC-GAN). In addition to the real/fake classifier used in vanilla GANs, our discriminator has an advanced auxiliary classifier which distinguishes each real class from an extra `fake' class. The `fake' class avoids mixing generated data with real data, which can potentially confuse the classification of real data as AC-GAN does, and makes the advanced auxiliary classifier behave as another real/fake classifier. As a result, FC-GAN can accelerate the process of differentiation of all classes, thus boost the convergence speed. Experimental results on image synthesis demonstrate our model is competitive in the quality of images generated while achieving a faster convergence rate.

##### Abstract (translated by Google)
除了生成对抗网络（GAN）的成功之外，条件GAN试图通过调整某些附加信息来更好地指导数据生成过程。受最近AC-GAN的启发，本文提出了一种快速收敛的条件GAN（FC-GAN）。除了在香草GAN中使用的真实/假分类器之外，我们的鉴别器还有一个先进的辅助分类器，可以将每个真实类与一个额外的“假”类区分开来。 “假”类避免了将生成的数据与真实数据混合，这可能会混淆AC-GAN所做的真实数据的分类，并使高级辅助分类器表现为另一个真实/伪分类器。因此，FC-GAN可以加快所有类别的分化过程，从而提高收敛速度。图像合成的实验结果表明，我们的模型在获得更快收敛速度​​的同时，在图像质量方面具有竞争力。

##### URL
[http://arxiv.org/abs/1805.01972](http://arxiv.org/abs/1805.01972)

##### PDF
[http://arxiv.org/pdf/1805.01972](http://arxiv.org/pdf/1805.01972)

