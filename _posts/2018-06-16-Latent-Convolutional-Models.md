---
layout: post
title: "Latent Convolutional Models"
date: 2018-06-16 19:31:32
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Embedding CNN
author: ShahRukh Athar, Evgeniy Burnaev, Victor Lempitsky
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new latent model of natural images that can be learned on large-scale datasets. The learning process provides a latent embedding for every image in the training dataset, as well as a deep convolutional network that maps the latent space to the image space. After training, the new model provides a strong and universal image prior for a variety of image restoration tasks such as large-hole inpainting, superresolution, and colorization. To model high-resolution natural images, our approach uses latent spaces of very high dimensionality (one to two orders of magnitude higher than previous latent image models). To tackle this high dimensionality, we use latent spaces with a special manifold structure (convolutional manifolds) parameterized by a ConvNet of a certain architecture. In the experiments, we compare the learned latent models with latent models learned by autoencoders, advanced variants of generative adversarial networks, and a strong baseline system using simpler parameterization of the latent space. Our model outperforms the competing approaches over a range of restoration tasks.

##### Abstract (translated by Google)
我们提出了一种可以在大型数据集上学习的自然图像的新潜在模型。学习过程为训练数据集中的每个图像提供潜在嵌入，以及将潜在空间映射到图像空间的深度卷积网络。在训练之后，新模型提供了强大而通用的图像，可用于各种图像恢复任务，如大孔修补，超分辨率和彩色化。为了对高分辨率的自然图像建模，我们的方法使用了非常高维的潜在空间（比先前的潜像模型高一到两个数量级）。为了解决这个高维问题，我们使用由特定体系结构的ConvNet参数化的特殊流形结构（卷积流形）的潜在空间。在实验中，我们将学习的潜在模型与自编码器学习的潜在模型，生成敌对网络的高级变体以及使用更简单的潜在空间参数化的强大基线系统进行比较。我们的模型胜过了一系列恢复任务的竞争方法。

##### URL
[http://arxiv.org/abs/1806.06284](http://arxiv.org/abs/1806.06284)

##### PDF
[http://arxiv.org/pdf/1806.06284](http://arxiv.org/pdf/1806.06284)

