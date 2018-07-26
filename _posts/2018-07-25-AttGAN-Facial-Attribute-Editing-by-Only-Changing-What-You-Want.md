---
layout: post
title: "AttGAN: Facial Attribute Editing by Only Changing What You Want"
date: 2018-07-25 10:08:00
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Face Classification
author: Zhenliang He, Wangmeng Zuo, Meina Kan, Shiguang Shan, Xilin Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Facial attribute editing aims to manipulate single or multiple attributes of a face image, i.e., to generate a new face with desired attributes while preserving other details. Recently, generative adversarial net (GAN) and encoder-decoder architecture are usually incorporated to handle this task with promising results. Based on the encoder-decoder architecture, facial attribute editing is achieved by decoding the latent representation of the given face conditioned on the desired attributes. Some existing methods attempt to establish an attribute-independent latent representation for further attribute editing. However, such attribute-independent constraint on the latent representation is excessive because it restricts the capacity of the latent representation and may result in information loss, leading to over-smooth and distorted generation. Instead of imposing constraints on the latent representation, in this work we apply an attribute classification constraint to the generated image to just guarantee the correct change of desired attributes, i.e., to "change what you want". Meanwhile, the reconstruction learning is introduced to preserve attribute-excluding details, in other words, to "only change what you want". Besides, the adversarial learning is employed for visually realistic editing. These three components cooperate with each other forming an effective framework for high quality facial attribute editing, referred as AttGAN. Furthermore, our method is also directly applicable for attribute intensity control and can be naturally extended for attribute style manipulation. Experiments on CelebA dataset show that our method outperforms the state-of-the-arts on realistic attribute editing with facial details well preserved.

##### Abstract (translated by Google)
面部属性编辑旨在操纵面部图像的单个或多个属性，即，在保留其他细节的同时生成具有期望属性的新面部。最近，通常采用生成对抗网（GAN）和编码器 - 解码器架构来处理该任务并获得有希望的结果。基于编码器 - 解码器架构，通过解码以期望属性为条件的给定面部的潜在表示来实现面部属性编辑。一些现有方法试图建立与属性无关的潜在表示以进行进一步的属性编辑。然而，对潜在表示的这种与属性无关的约束是过度的，因为它限制了潜在表示的容量并且可能导致信息丢失，导致过度平滑和失真的生成。在这项工作中，我们不是对潜在表示施加约束，而是对生成的图像应用属性分类约束，以保证所需属性的正确变化，即“改变你想要的”。同时，引入重建学习以保留属性排除细节，换句话说，“仅改变你想要的东西”。此外，对抗性学习用于视觉上逼真的编辑。这三个组件相互配合，形成高质量面部属性编辑的有效框架，称为AttGAN。此外，我们的方法也可以直接应用于属性强度控制，并且可以自然地扩展到属性样式操作。 CelebA数据集上的实验表明，我们的方法在现实属性编辑方面优于现有技术，面部细节保存完好。

##### URL
[http://arxiv.org/abs/1711.10678](http://arxiv.org/abs/1711.10678)

##### PDF
[http://arxiv.org/pdf/1711.10678](http://arxiv.org/pdf/1711.10678)

