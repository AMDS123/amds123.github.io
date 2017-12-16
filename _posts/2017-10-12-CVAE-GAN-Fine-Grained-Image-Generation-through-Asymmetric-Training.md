---
layout: post
title: "CVAE-GAN: Fine-Grained Image Generation through Asymmetric Training"
date: 2017-10-12 15:19:40
categories: arXiv_CV
tags: arXiv_CV Adversarial Super_Resolution GAN Face Relation Recognition Face_Recognition
author: Jianmin Bao, Dong Chen, Fang Wen, Houqiang Li, Gang Hua
mathjax: true
---

* content
{:toc}

##### Abstract
We present variational generative adversarial networks, a general learning framework that combines a variational auto-encoder with a generative adversarial network, for synthesizing images in fine-grained categories, such as faces of a specific person or objects in a category. Our approach models an image as a composition of label and latent attributes in a probabilistic model. By varying the fine-grained category label fed into the resulting generative model, we can generate images in a specific category with randomly drawn values on a latent attribute vector. Our approach has two novel aspects. First, we adopt a cross entropy loss for the discriminative and classifier network, but a mean discrepancy objective for the generative network. This kind of asymmetric loss function makes the GAN training more stable. Second, we adopt an encoder network to learn the relationship between the latent space and the real image space, and use pairwise feature matching to keep the structure of generated images. We experiment with natural images of faces, flowers, and birds, and demonstrate that the proposed models are capable of generating realistic and diverse samples with fine-grained category labels. We further show that our models can be applied to other tasks, such as image inpainting, super-resolution, and data augmentation for training better face recognition models.

##### Abstract (translated by Google)
我们提出变分生成对抗网络，这是一个将变分自动编码器与生成对抗网络相结合的通用学习框架，用于合成细粒度类别（如特定人脸或某个类别中的对象）的图像。我们的方法将图像建模为概率模型中标签和潜在属性的组合。通过改变生成的生成模型中的细粒度类别标签，我们可以生成一个特定类别的图像，并在潜在的属性向量上随机绘制值。我们的方法有两个新颖的方面。首先，我们对判别分类网络采用交叉熵损失，而对于生成网络则采用平均差异目标。这种非对称损失函数使得GAN训练更加稳定。其次，采用编码器网络学习潜在空间与实际图像空间之间的关系，并采用成对特征匹配来保持生成图像的结构。我们对脸部，花朵和鸟类的自然图像进行了实验，并证明了所提出的模型能够生成具有细粒度类别标签的逼真和多样化的样本。我们进一步表明，我们的模型可以应用于其他任务，如图像修复，超分辨率和数据增强训练更好的人脸识别模型。

##### URL
[https://arxiv.org/abs/1703.10155](https://arxiv.org/abs/1703.10155)

##### PDF
[https://arxiv.org/pdf/1703.10155](https://arxiv.org/pdf/1703.10155)

