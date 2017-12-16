---
layout: post
title: "Unsupervised 3D Reconstruction from a Single Image via Adversarial Learning"
date: 2017-11-26 00:12:43
categories: arXiv_CV
tags: arXiv_CV Adversarial Embedding CNN Deep_Learning
author: Lingjing Wang, Yi Fang
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advancements in deep learning opened new opportunities for learning a high-quality 3D model from a single 2D image given sufficient training on large-scale data sets. However, the significant imbalance between available amount of images and 3D models, and the limited availability of labeled 2D image data (i.e. manually annotated pairs between images and their corresponding 3D models), severely impacts the training of most supervised deep learning methods in practice. In this paper, driven by a novel design of adversarial networks, we have developed an unsupervised learning paradigm to reconstruct 3D models from a single 2D image, which is free of manually annotated pairwise input image and its associated 3D model. Particularly, the paradigm begins with training an adaption network via autoencoder with adversarial loss, which embeds unpaired 2D synthesized image domain with real world image domain to a shared latent vector space. Then, we jointly train a 3D deconvolutional network to transform the latent vector space to the 3D object space together with the embedding process. Our experiments verify our network's robust and superior performance in handling 3D volumetric object generation from a single 2D image.

##### Abstract (translated by Google)
深度学习方面的最新进展为从大型数据集提供足够训练的单个2D图像开始学习高质量3D模型提供了新的机会。然而，图像和3D模型的可用量之间的显着不平衡以及标记的2D图像数据（即，图像与其对应的3D模型之间的手动注释的对）的有限可用性严重影响了实践中大多数受监督的深度学习方法的训练。在本文中，由一个新颖的对抗网络设计驱动，我们已经开发了一个无监督的学习范式，从一个单一的二维图像，这是没有手动注释成对输入图像及其相关的三维模型的三维模型重建。具体而言，该范式首先通过具有对抗性损失的自编码器对自适应网络进行训练，其将未配对的2D合成图像域与真实世界图像域嵌入共享的潜在向量空间。然后，我们联合训练一个3D去卷积网络，将潜在向量空间与嵌入过程一起转化为三维对象空间。我们的实验验证了我们的网络在处理来自单个2D图像的3D体积对象生成方面的强大和出众的性能。

##### URL
[https://arxiv.org/abs/1711.09312](https://arxiv.org/abs/1711.09312)

##### PDF
[https://arxiv.org/pdf/1711.09312](https://arxiv.org/pdf/1711.09312)

