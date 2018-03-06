---
layout: post
title: "Memorization Precedes Generation: Learning Unsupervised GANs with Memory Networks"
date: 2018-03-05 05:17:42
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Optimization Memory_Networks
author: Youngjin Kim, Minjung Kim, Gunhee Kim
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an approach to address two issues that commonly occur during training of unsupervised GANs. First, since GANs use only a continuous latent distribution to embed multiple classes or clusters of data, they often do not correctly handle the structural discontinuity between disparate classes in a latent space. Second, discriminators of GANs easily forget about past generated samples by generators, incurring instability during adversarial training. We argue that these two infamous problems of unsupervised GAN training can be largely alleviated by a learnable memory network to which both generators and discriminators can access. Generators can effectively learn representation of training samples to understand underlying cluster distributions of data, which ease the structure discontinuity problem. At the same time, discriminators can better memorize clusters of previously generated samples, which mitigate the forgetting problem. We propose a novel end-to-end GAN model named memoryGAN, which involves a memory network that is unsupervisedly trainable and integrable to many existing GAN models. With evaluations on multiple datasets such as Fashion-MNIST, CelebA, CIFAR10, and Chairs, we show that our model is probabilistically interpretable, and generates realistic image samples of high visual fidelity. The memoryGAN also achieves the state-of-the-art inception scores over unsupervised GAN models on the CIFAR10 dataset, without any optimization tricks and weaker divergences.

##### Abstract (translated by Google)
我们提出一种方法来解决在无监督GAN训练期间通常发生的两个问题。首先，由于GAN仅使用连续的潜在分布来嵌入多个类或数据集，因此它们通常不能正确处理潜在空间中不同类之间的结构不连续性。其次，GAN的鉴别者很容易忘记发电机产生的过去的样本，在对抗训练期间引起不稳定。我们认为，无监督的GAN训练这两个臭名昭着的问题可以通过一个学习型记忆网络大大缓解，发生器和鉴别器都可以访问这个记忆网络。生成器可以有效地学习训练样本的表示，以便了解数据的基本聚类分布，从而缓解结构不连续问题。同时，鉴别器可以更好地记忆先前生成的样本群集，从而减轻遗忘问题。我们提出了一种名为memoryGAN的新型端到端GAN模型，该模型涉及一个无监督地训练和可以与许多现有GAN模型集成的记忆网络。通过对Fashion-MNIST，CelebA，CIFAR10和Chairs等多个数据集的评估，我们展示了我们的模型具有概率可解释性，并生成逼真的高视觉保真度图像样本。 memoryGAN还可以在CIFAR10数据集上的无监督GAN模型上实现最先进的初始分数，没有任何优化技巧和较弱的分歧。

##### URL
[https://arxiv.org/abs/1803.01500](https://arxiv.org/abs/1803.01500)

##### PDF
[https://arxiv.org/pdf/1803.01500](https://arxiv.org/pdf/1803.01500)

