---
layout: post
title: "Generative Adversarial Autoencoder Networks"
date: 2018-03-23 17:06:26
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge GAN
author: Ngoc-Trung Tran, Tuan-Anh Bui, Ngai-Man Cheung
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce an effective model to overcome the problem of mode collapse when training Generative Adversarial Networks (GAN). Firstly, we propose a new generator objective that finds it better to tackle mode collapse. And, we apply an independent Autoencoders (AE) to constrain the generator and consider its reconstructed samples as "real" samples to slow down the convergence of discriminator that enables to reduce the gradient vanishing problem and stabilize the model. Secondly, from mappings between latent and data spaces provided by AE, we further regularize AE by the relative distance between the latent and data samples to explicitly prevent the generator falling into mode collapse setting. This idea comes when we find a new way to visualize the mode collapse on MNIST dataset. To the best of our knowledge, our method is the first to propose and apply successfully the relative distance of latent and data samples for stabilizing GAN. Thirdly, our proposed model, namely Generative Adversarial Autoencoder Networks (GAAN), is stable and has suffered from neither gradient vanishing nor mode collapse issues, as empirically demonstrated on synthetic, MNIST, MNIST-1K, CelebA and CIFAR-10 datasets. Experimental results show that our method can approximate well multi-modal distribution and achieve better results than state-of-the-art methods on these benchmark datasets. Our model implementation is published here: this https URL

##### Abstract (translated by Google)
我们引入了一个有效的模型来克服训练生成对抗网络（GAN）时模式崩溃的问题。首先，我们提出一个新的发电机目标，发现它更好地处理模式崩溃。并且，我们应用独立的自动编码器（AE）来限制发生器，并将其重构样本视为“真实”样本，以减慢鉴别器的收敛，从而减少梯度消失问题并稳定模型。其次，从AE提供的潜在和数据空间之间的映射，我们进一步通过潜在和数据样本之间的相对距离来规范AE，以明确防止发生器陷入模式崩溃设置。当我们找到一种可视化MNIST数据集模式崩溃的新方法时，这个想法就来了。就我们所知，我们的方法是第一个成功提出并应用潜在和数据样本的相对距离来稳定GAN的方法。第三，我们提出的模型，即生成对抗自动编码器网络（GAAN），在合成，MNIST，MNIST-1K，CelebA和CIFAR-10数据集上经验证明，它是稳定的，既没有梯度消失也没有模式崩溃问题。实验结果表明，我们的方法可以近似良好的多模态分布，并取得比这些基准数据集上最先进的方法更好的结果。我们的模型实现发布在这里：https https

##### URL
[https://arxiv.org/abs/1803.08887](https://arxiv.org/abs/1803.08887)

##### PDF
[https://arxiv.org/pdf/1803.08887](https://arxiv.org/pdf/1803.08887)

