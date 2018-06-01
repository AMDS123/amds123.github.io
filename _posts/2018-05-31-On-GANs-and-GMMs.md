---
layout: post
title: "On GANs and GMMs"
date: 2018-05-31 13:37:59
categories: arXiv_CV
tags: arXiv_CV Attention GAN Inference
author: Eitan Richardson, Yair Weiss
mathjax: true
---

* content
{:toc}

##### Abstract
A longstanding problem in machine learning is to find unsupervised methods that can learn the statistical structure of high dimensional signals. In recent years, GANs have gained much attention as a possible solution to the problem, and in particular have shown the ability to generate remarkably realistic high resolution sampled images. At the same time, many authors have pointed out that GANs may fail to model the full distribution ("mode collapse") and that using the learned models for anything other than generating samples may be very difficult. In this paper, we examine the utility of GANs in learning statistical models of images by comparing them to perhaps the simplest statistical model, the Gaussian Mixture Model. First, we present a simple method to evaluate generative models based on relative proportions of samples that fall into predetermined bins. Unlike previous automatic methods for evaluating models, our method does not rely on an additional neural network nor does it require approximating intractable computations. Second, we compare the performance of GANs to GMMs trained on the same datasets. While GMMs have previously been shown to be successful in modeling small patches of images, we show how to train them on full sized images despite the high dimensionality. Our results show that GMMs can generate realistic samples (although less sharp than those of GANs) but also capture the full distribution, which GANs fail to do. Furthermore, GMMs allow efficient inference and explicit representation of the underlying statistical structure. Finally, we discuss how a pix2pix network can be used to add high-resolution details to GMM samples while maintaining the basic diversity.

##### Abstract (translated by Google)
机器学习中长期存在的问题是找到可以学习高维信号统计结构的无监督方法。近年来，GAN作为该问题的可能解决方案受到了很多关注，特别是已经显示出生成非常逼真的高分辨率采样图像的能力。与此同时，许多作者指出，GAN可能无法模拟完整分布（“模式崩溃”），并且使用学习模型进行除生成样本之外的任何其他内容都可能非常困难。在本文中，我们通过将GAN与最简单的统计模型 - 高斯混合模型（Gaussian Mixture Model）进行比较，来研究GAN在学习图像统计模型中的效用。首先，我们提出一种简单的方法来评估生成模型，其基于落入预定分箱的样本的相对比例。与以前用于评估模型的自动方法不同，我们的方法不依赖于额外的神经网络，也不需要近似难以计算的计算。其次，我们比较GAN与在相同数据集上训练的GMM的性能。尽管GMMs先前已被证明可以成功地对小块图像进行建模，但我们展示了如何以尽可能高的维度对全尺寸图像进行训练。我们的研究结果表明，GMM可以生成逼真的样本（虽然不如GAN的那些尖锐），但也捕获了GAN无法做到的全部分布。此外，GMM允许有效的推断和明确的基本统计结构表示。最后，我们讨论如何使用pix2pix网络向GMM样本添加高分辨率细节，同时保持基本的多样性。

##### URL
[http://arxiv.org/abs/1805.12462](http://arxiv.org/abs/1805.12462)

##### PDF
[http://arxiv.org/pdf/1805.12462](http://arxiv.org/pdf/1805.12462)

