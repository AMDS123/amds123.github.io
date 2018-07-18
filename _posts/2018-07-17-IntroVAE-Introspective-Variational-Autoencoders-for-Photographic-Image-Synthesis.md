---
layout: post
title: "IntroVAE: Introspective Variational Autoencoders for Photographic Image Synthesis"
date: 2018-07-17 11:37:31
categories: arXiv_CV
tags: arXiv_CV GAN Inference
author: Huaibo Huang, Zhihang Li, Ran He, Zhenan Sun, Tieniu Tan
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel introspective variational autoencoder (IntroVAE) model for synthesizing high-resolution photographic images. IntroVAE is capable of self-evaluating the quality of its generated samples and improving itself accordingly. Its inference and generator models are jointly trained in an introspective way. On one hand, the generator is required to reconstruct the input images from the noisy outputs of the inference model as normal VAEs. On the other hand, the inference model is encouraged to classify between the generated and real samples while the generator tries to fool it as GANs. These two famous generative frameworks are integrated in a simple yet efficient single-stream architecture that can be trained in a single stage. IntroVAE preserves the advantages of VAEs, such as stable training and nice latent manifold. Unlike most other hybrid models of VAEs and GANs, IntroVAE requires no extra discriminators, because the inference model itself serves as a discriminator to distinguish between the generated and real samples. Experiments demonstrate that our method produces high-resolution photo-realistic images (e.g., CELEBA images at \(1024^{2}\)), which are comparable to or better than the state-of-the-art GANs.

##### Abstract (translated by Google)
我们提出了一种新的内省变分自动编码器（IntroVAE）模型，用于合成高分辨率的摄影图像。 IntroVAE能够自我评估其生成的样品的质量并相应地改进自身。它的推理和发电机模型以内省的方式共同训练。一方面，需要发生器将来自推理模型的噪声输出的输入图像重建为正常VAE。另一方面，鼓励推理模型在生成的样本和实际样本之间进行分类，而生成器试图将其作为GAN欺骗。这两个着名的生成框架集成在一个简单而有效的单流架构中，可以在一个阶段进行训练。 IntroVAE保留了VAE的优点，例如稳定的训练和漂亮的潜在歧管。与VAE和GAN的大多数其他混合模型不同，IntroVAE不需要额外的鉴别器，因为推理模型本身用作区分生成和实际样本的鉴别器。实验证明，我们的方法产生高分辨率照片般逼真的图像（例如，在\（1024 ^ {2} \））的CELEBA图像，其与现有技术的GAN相当或更好。

##### URL
[http://arxiv.org/abs/1807.06358](http://arxiv.org/abs/1807.06358)

##### PDF
[http://arxiv.org/pdf/1807.06358](http://arxiv.org/pdf/1807.06358)

