---
layout: post
title: "Generative Adversarial Networks with Decoder-Encoder Output Noise"
date: 2018-07-11 01:50:17
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN CNN Inference
author: Guoqiang Zhong, Wei Gao, Yongbin Liu, Youzhao Yang
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, research on image generation methods has been developing fast. The auto-encoding variational Bayes method (VAEs) was proposed in 2013, which uses variational inference to learn a latent space from the image database and then generates images using the decoder. The generative adversarial networks (GANs) came out as a promising framework, which uses adversarial training to improve the generative ability of the generator. However, the generated pictures by GANs are generally blurry. The deep convolutional generative adversarial networks (DCGANs) were then proposed to leverage the quality of generated images. Since the input noise vectors are randomly sampled from a Gaussian distribution, the generator has to map from a whole normal distribution to the images. This makes DCGANs unable to reflect the inherent structure of the training data. In this paper, we propose a novel deep model, called generative adversarial networks with decoder-encoder output noise (DE-GANs), which takes advantage of both the adversarial training and the variational Bayesain inference to improve the performance of image generation. DE-GANs use a pre-trained decoder-encoder architecture to map the random Gaussian noise vectors to informative ones and pass them to the generator of the adversarial networks. Since the decoder-encoder architecture is trained by the same images as the generators, the output vectors could carry the intrinsic distribution information of the original images. Moreover, the loss function of DE-GANs is different from GANs and DCGANs. A hidden-space loss function is added to the adversarial loss function to enhance the robustness of the model. Extensive empirical results show that DE-GANs can accelerate the convergence of the adversarial training process and improve the quality of the generated images.

##### Abstract (translated by Google)
近年来，对图像生成方法的研究正在迅速发展。自动编码变分贝叶斯方法（VAE）于2013年提出，它使用变分推理从图像数据库中学习潜在空间，然后使用解码器生成图像。生成对抗网络（GANs）作为一个有前途的框架出现，它使用对抗训练来提高发电机的生成能力。然而，GAN生成的图片通常是模糊的。然后提出深度卷积生成对抗网络（DCGAN）来利用生成图像的质量。由于输入噪声矢量是从高斯分布中随机采样的，因此发生器必须从整个正态分布映射到图像。这使得DCGAN无法反映训练数据的固有结构。在本文中，我们提出了一种新的深度模型，称为具有解码器 - 编码器输出噪声（DE-GAN）的生成对抗网络，它利用对抗训练和变分贝叶斯推断来提高图像生成的性能。 DE-GAN使用预先训练的解码器 - 编码器架构将随机高斯噪声向量映射到信息性高斯噪声向量并将它们传递到对抗性网络的生成器。由于解码器 - 编码器架构由与生成器相同的图像训练，因此输出矢量可以携带原始图像的固有分布信息。此外，DE-GAN的损失功能与GAN和DCGAN不同。隐藏空间损失函数被添加到对抗性损失函数中以增强模型的稳健性。大量的实证结果表明，DE-GAN可以加速对抗训练过程的收敛，提高生成图像的质量。

##### URL
[http://arxiv.org/abs/1807.03923](http://arxiv.org/abs/1807.03923)

##### PDF
[http://arxiv.org/pdf/1807.03923](http://arxiv.org/pdf/1807.03923)

