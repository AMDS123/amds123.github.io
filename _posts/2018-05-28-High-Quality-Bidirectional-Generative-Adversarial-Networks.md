---
layout: post
title: "High Quality Bidirectional Generative Adversarial Networks"
date: 2018-05-28 00:22:18
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Inference
author: Duhyeon Bang, Hyunjung Shim
mathjax: true
---

* content
{:toc}

##### Abstract
Generative adversarial networks (GANs) have achieved outstanding success in generating the high quality data. Focusing on the generation process, existing GANs investigate unidirectional mapping from the latent vector to the data. Later, various studies point out that the latent space of GANs is semantically meaningful and can be utilized in advanced data analysis and manipulation. In order to analyze the real data in the latent space of GANs, it is necessary to investigate the inverse generation mapping from the data to the latent vector. To tackle this problem, the bidirectional generative models introduce an encoder to enable the inverse path of generation process. Unfortunately, this effort leads to the degradation of generation quality because the imperfect generator rather interferes the encoder training and vice versa. In this paper, we propose a new inference model that estimates the latent vector from the feature of GAN discriminator. While existing bidirectional models learns the image to latent translation, our algorithm formulates this inference mapping by the feature to latent translation. It is important to note that training of our model is independent of the GAN training. Owing to the attractive nature of this independency, the proposed algorithm can generate the high quality samples identical to those of unidirectional GANs and also reconstruct the original data faithfully. Moreover, our algorithm can be employed to any unidirectional GAN, even the pre-traind GANs.

##### Abstract (translated by Google)
生成对抗网络（GAN）在生成高质量数据方面取得了显着的成功。关注生成过程，现有的GAN调查从潜在向量到数据的单向映射。后来各种研究指出，GAN的潜在空间在语义上是有意义的，可用于高级数据分析和操作。为了分析GAN潜在空间中的真实数据，有必要研究从数据到潜在向量的逆生成映射。为了解决这个问题，双向生成模型引入了编码器来实现生成过程的反向路径。不幸的是，这种努力会导致发电质量的下降，因为不完善的发电机会干扰编码器的培训，反之亦然。在本文中，我们提出了一个新的推断模型，用GAN鉴别器的特征来估计潜在向量。虽然现有的双向模型将图像学习为潜在的翻译，但我们的算法通过特征将该推理映射制定为潜在的翻译。需要注意的是，我们的模型的培训与GAN培训无关。由于这种独立性的吸引力，所提出的算法可以生成与单向GAN相同的高质量样本，并且还忠实地重建原始数据。此外，我们的算法可以用于任何单向GAN，甚至是预训练的GAN。

##### URL
[http://arxiv.org/abs/1805.10717](http://arxiv.org/abs/1805.10717)

##### PDF
[http://arxiv.org/pdf/1805.10717](http://arxiv.org/pdf/1805.10717)

