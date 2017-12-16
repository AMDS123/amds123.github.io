---
layout: post
title: "Channel-Recurrent Variational Autoencoders"
date: 2017-06-12 17:01:34
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Face Inference Classification
author: Wenling Shang, Kihyuk Sohn, Zeynep Akata, Yuandong Tian
mathjax: true
---

* content
{:toc}

##### Abstract
Variational Autoencoder (VAE) is an efficient framework in modeling natural images with probabilistic latent spaces. However, when the input spaces become complex, VAE becomes less effective, potentially due to the oversimplification of its latent space construction. In this paper, we propose to integrate recurrent connections across channels to both inference and generation steps of VAE. Sequentially building up the complexity of high-level features in this way allows us to capture global-to-local and coarse-to-fine structures of the input data spaces. We show that our channel-recurrent VAE improves existing approaches in multiple aspects: (1) it attains lower negative log-likelihood than standard VAE on MNIST; when trained adversarially, (2) it generates face and bird images with substantially higher visual quality than the state-of-the-art VAE-GAN and (3) channel-recurrency allows learning more interpretable representations; finally (4) it achieves competitive classification results on STL-10 in a semi-supervised setup.

##### Abstract (translated by Google)
变分自动编码器（VAE）是用概率潜在空间建模自然图像的有效框架。然而，当输入空间变得复杂时，VAE变得不那么有效，这可能是由于它的潜在空间结构过于简单。在本文中，我们建议将跨渠道的经常性连接集成到VAE的推理和生成步骤中。以这种方式顺序构建高级特征的复杂性使我们能够捕获输入数据空间的全局到局部和粗到精细的结构。我们显示，我们的频道复发性VAE在多个方面改进了现有的方法：（1）在MNIST上获得比标准VAE更低的负对数似然性; （2）它产生比现有技术的VAE-GAN具有更高视觉质量的脸部和鸟的图像，以及（3）频道重现允许学习更多可解释的表示;最后（4）在半监督的环境下，STL-10达到了有竞争力的分类结果。

##### URL
[https://arxiv.org/abs/1706.03729](https://arxiv.org/abs/1706.03729)

##### PDF
[https://arxiv.org/pdf/1706.03729](https://arxiv.org/pdf/1706.03729)

