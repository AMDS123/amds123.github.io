---
layout: post
title: "Generative Adversarial Networks for Image-to-Image Translation on Multi-Contrast MR Images - A Comparison of CycleGAN and UNIT"
date: 2018-06-20 14:56:10
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Classification Deep_Learning Quantitative
author: Per Welander, Simon Karlsson, Anders Eklund
mathjax: true
---

* content
{:toc}

##### Abstract
In medical imaging, a general problem is that it is costly and time consuming to collect high quality data from healthy and diseased subjects. Generative adversarial networks (GANs) is a deep learning method that has been developed for synthesizing data. GANs can thereby be used to generate more realistic training data, to improve classification performance of machine learning algorithms. Another application of GANs is image-to-image translations, e.g. generating magnetic resonance (MR) images from computed tomography (CT) images, which can be used to obtain multimodal datasets from a single modality. Here, we evaluate two unsupervised GAN models (CycleGAN and UNIT) for image-to-image translation of T1- and T2-weighted MR images, by comparing generated synthetic MR images to ground truth images. We also evaluate two supervised models; a modification of CycleGAN and a pure generator model. A small perceptual study was also performed to evaluate how visually realistic the synthesized images are. It is shown that the implemented GAN models can synthesize visually realistic MR images (incorrectly labeled as real by a human). It is also shown that models producing more visually realistic synthetic images not necessarily have better quantitative error measurements, when compared to ground truth data. Code is available at https://github.com/simontomaskarlsson/GAN-MRI

##### Abstract (translated by Google)
在医学成像中，一个普遍的问题是从健康和患病的受试者收集高质量的数据是昂贵和耗时的。生成对抗网络（GAN）是一种深度学习方法，用于合成数据。因此可以使用GAN生成更逼真的训练数据，以改善机器学习算法的分类性能。 GAN的另一个应用是图像到图像的翻译，例如，从计算机断层扫描（CT）图像生成磁共振（MR）图像，其可用于从单一模态获得多模态数据集。在这里，我们通过比较生成的合成MR图像和地面实况图像，评估两个无监督的GAN模型（CycleGAN和UNIT）用于T1和T2加权MR图像的图像到图像平移。我们也评估两个监督模型; CycleGAN的修改和纯生成器模型。还进行了一项小型感知研究，以评估合成图像的视觉真实感。结果表明，实施的GAN模型可以合成视觉上真实的MR图像（被人错误地标记为真实的）。还表明，与地面实况数据相比，产生更多视觉逼真合成图像的模型不一定具有更好的定量误差测量。代码可在https://github.com/simontomaskarlsson/GAN-MRI获得

##### URL
[http://arxiv.org/abs/1806.07777](http://arxiv.org/abs/1806.07777)

##### PDF
[http://arxiv.org/pdf/1806.07777](http://arxiv.org/pdf/1806.07777)

