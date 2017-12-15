---
layout: post
title: "Generative Image Modeling using Style and Structure Adversarial Networks"
date: 2016-07-26 03:54:23
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Face
author: Xiaolong Wang, Abhinav Gupta
mathjax: true
---

* content
{:toc}

##### Abstract
Current generative frameworks use end-to-end learning and generate images by sampling from uniform noise distribution. However, these approaches ignore the most basic principle of image formation: images are product of: (a) Structure: the underlying 3D model; (b) Style: the texture mapped onto structure. In this paper, we factorize the image generation process and propose Style and Structure Generative Adversarial Network (S^2-GAN). Our S^2-GAN has two components: the Structure-GAN generates a surface normal map; the Style-GAN takes the surface normal map as input and generates the 2D image. Apart from a real vs. generated loss function, we use an additional loss with computed surface normals from generated images. The two GANs are first trained independently, and then merged together via joint learning. We show our S^2-GAN model is interpretable, generates more realistic images and can be used to learn unsupervised RGBD representations.

##### Abstract (translated by Google)
当前的生成框架使用端到端的学习，并通过从均匀的噪声分布采样来生成图像。然而，这些方法忽略了图像形成的最基本的原则：图像是以下的产物：（a）结构：潜在的3D模型; （b）样式：映射到结构上的纹理。在本文中，我们将图像生成过程分解，并提出风格和结构生成对抗网络（S ^ 2-GAN）。我们的S ^ 2-GAN有两个组件：Structure-GAN生成一个曲面法线贴图; Style-GAN将表面法线贴图作为输入并生成2D图像。除了实际与生成的损失函数之外，我们还使用所生成图像的计算表面法线的额外损失。两个GAN首先独立训练，然后通过联合学习合并在一起。我们展示了我们的S ^ 2-GAN模型是可解释的，生成更逼真的图像，并且可以用于学习无监督的RGBD表示。

##### URL
[https://arxiv.org/abs/1603.05631](https://arxiv.org/abs/1603.05631)

##### PDF
[https://arxiv.org/pdf/1603.05631](https://arxiv.org/pdf/1603.05631)

