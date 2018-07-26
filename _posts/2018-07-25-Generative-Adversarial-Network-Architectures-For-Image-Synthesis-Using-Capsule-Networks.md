---
layout: post
title: "Generative Adversarial Network Architectures For Image Synthesis Using Capsule Networks"
date: 2018-07-25 07:55:20
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN CNN Relation
author: Yash Upadhyay, Paul Schrater
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose Generative Adversarial Network (GAN) architectures using Capsule Networks for conditional and random image-synthesis. Capsule Networks encode meta-properties and spatial relationships between the features of the image, which helps it become a more powerful critic in comparison to the Convolutional Neural Networks (CNNs) used in current architectures for image synthesis. Our architectures use losses analogous to Wasserstein loss and Capsule Networks, which prove to be a more effective critic in comparison to CNNs. Thus, our proposed GAN architectures learn the data manifold much faster and therefore, show significant reduction in the number of training samples required to train when compared to the current work horses for image synthesis, DCGANs and its variants which utilize CNNs as discriminators. Also, our architecture generalizes over the datasets' manifold much better because of dynamic routing between capsules which is a more robust algorithm for feature globalization in comparison to max-pooling used by CNNs. This helps synthesize more diverse, yet visually accurate images. We have demonstrated the performance of our architectures over MNIST, Fashion-MNIST and their variants and compared them with the images synthesised using Improved Wasserstein GANs that use CNNs.

##### Abstract (translated by Google)
在本文中，我们提出使用胶囊网络进行条件和随机图像合成的生成对抗网络（GAN）体系结构。胶囊网络对图像特征之间的元属性和空间关系进行编码，与当前用于图像合成的体系结构中使用的卷积神经网络（CNN）相比，它有助于使其成为更强大的批评者。我们的架构使用类似于Wasserstein损失和Capsule Networks的损失，与CNN相比，它被证明是更有效的批评者。因此，我们提出的GAN架构更快地学习数据流形，因此，与用于图像合成的当前工作马，DCGAN及其利用CNN作为鉴别器的变体相比，显示训练所需的训练样本的数量显着减少。此外，由于胶囊之间的动态路由，我们的体系结构更好地概括了数据集的流形，与CNN使用的最大池相比，这是一种更强大的特征全球化算法。这有助于合成更多样化但视觉上准确的图像。我们已经证明了我们的架构相对于MNIST，Fashion-MNIST及其变体的性能，并将它们与使用改进的Wasserstein GAN使用CNN合成的图像进行了比较。

##### URL
[http://arxiv.org/abs/1806.03796](http://arxiv.org/abs/1806.03796)

##### PDF
[http://arxiv.org/pdf/1806.03796](http://arxiv.org/pdf/1806.03796)

