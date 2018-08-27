---
layout: post
title: "Improved ArtGAN for Conditional Synthesis of Natural Image and Artwork"
date: 2018-08-23 15:10:59
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Wei Ren Tan, Chee Seng Chan, Hernan Aguirre, Kiyoshi Tanaka
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a series of new approaches to improve Generative Adversarial Network (GAN) for conditional image synthesis and we name the proposed model as ArtGAN. One of the key innovation of ArtGAN is that, the gradient of the loss function w.r.t. the label (randomly assigned to each generated image) is back-propagated from the categorical discriminator to the generator. With the feedback from the label information, the generator is able to learn more efficiently and generate image with better quality. Inspired by recent works, an autoencoder is incorporated into the categorical discriminator for additional complementary information. Last but not least, we introduce a novel strategy to improve the image quality. In the experiments, we evaluate ArtGAN on CIFAR-10 and STL-10 via ablation studies. The empirical results showed that our proposed model outperforms the state-of-the-art results on CIFAR-10 in terms of Inception score. Qualitatively, we demonstrate that ArtGAN is able to generate plausible-looking images on Oxford-102 and CUB-200, as well as able to draw realistic artworks based on style, artist, and genre. The source code and models are available at: https://github.com/cs-chan/ArtGAN

##### Abstract (translated by Google)
本文提出了一系列改进条件图像合成的生成对抗网络（GAN）的新方法，并将所提出的模型命名为ArtGAN。 ArtGAN的关键创新之一是损耗函数的梯度w.r.t.标签（随机分配给每个生成的图像）​​从分类鉴别器反向传播到生成器。利用来自标签信息的反馈，生成器能够更有效地学习并生成具有更好质量的图像。受近期工作的启发，自动编码器被纳入分类鉴别器中以获得额外的补充信息。最后但并非最不重要的是，我们引入了一种改善图像质量的新策略。在实验中，我们通过消融研究评估了CIFAR-10和STL-10上的ArtGAN。实证结果表明，我们提出的模型在初始得分方面优于CIFAR-10的最新结果。定性地说，我们证明了ArtGAN能够在Oxford-102和CUB-200上生成看似合理的图像，并能够根据风格，艺术家和流派绘制逼真的艺术作品。源代码和模型可从以下网址获得：https：//github.com/cs-chan/ArtGAN

##### URL
[http://arxiv.org/abs/1708.09533](http://arxiv.org/abs/1708.09533)

##### PDF
[http://arxiv.org/pdf/1708.09533](http://arxiv.org/pdf/1708.09533)

