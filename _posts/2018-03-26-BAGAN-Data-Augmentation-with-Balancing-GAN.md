---
layout: post
title: "BAGAN: Data Augmentation with Balancing GAN"
date: 2018-03-26 15:20:56
categories: arXiv_CV
tags: arXiv_CV GAN Image_Classification Classification
author: Giovanni Mariani, Florian Scheidegger, Roxana Istrate, Costas Bekas, Cristiano Malossi
mathjax: true
---

* content
{:toc}

##### Abstract
Image classification datasets are often imbalanced, characteristic that negatively affects the accuracy of deeplearning classifiers. In this work we propose balancing GANs (BAGANs) as an augmentation tool to restore balance in imbalanced datasets. This is challenging because the few minority-class images may not be enough to train a GAN. We overcome this issue by including during training all available images of majority and minority classes. The generative model learns useful features from majority classes and uses these to generate images for minority classes. We apply class-conditioning in the latent space to drive the generation process towards a target class. Additionally, we couple GANs with autoencoding techniques to reduce the risk of collapsing toward the generation of few foolish examples. We compare the proposed methodology with state-of-the-art GANs and demonstrate that BAGAN generates images of superior quality when trained with an imbalanced dataset.

##### Abstract (translated by Google)
图像分类数据集通常是不平衡的，其特征会对深度分类器的准确性产生负面影响。在这项工作中，我们建议平衡GAN（BAGAN）作为增强工具来恢复不平衡数据集中的平衡。这是具有挑战性的，因为少数几个级别的图像可能不足以训练GAN。我们通过在培训所有可用的多数和少数人群的图像期间解决了这个问题。生成模型从大多数类学习有用的特征，并使用它们为少数类生成图像。我们在潜在空间中应用类调节来驱动目标类的生成过程。此外，我们将GAN与自动编码技术结合在一起，以减少面向少数愚蠢示例的崩溃风险。我们将所提出的方法与最先进的GAN进行比较，并证明BAGAN在使用不平衡数据集进行训练时会生成优质图像。

##### URL
[https://arxiv.org/abs/1803.09655](https://arxiv.org/abs/1803.09655)

##### PDF
[https://arxiv.org/pdf/1803.09655](https://arxiv.org/pdf/1803.09655)

