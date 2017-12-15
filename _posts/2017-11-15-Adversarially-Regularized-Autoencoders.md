---
layout: post
title: "Adversarially Regularized Autoencoders"
date: 2017-11-15 05:41:04
categories: arXiv_CL
tags: arXiv_CL Adversarial GAN Style_Transfer Represenation_Learning RNN Relation
author: Junbo (Jake)Zhao, Yoon Kim, Kelly Zhang, Alexander M. Rush, Yann LeCun
mathjax: true
---

* content
{:toc}

##### Abstract
While autoencoders are a key technique in representation learning for continuous structures, such as images or wave forms, developing general-purpose autoencoders for discrete structures, such as text sequence or discretized images, has proven to be more challenging. In particular, discrete inputs make it more difficult to learn a smooth encoder that preserves the complex local relationships in the input space. In this work, we propose an adversarially regularized autoencoder (ARAE) with the goal of learning more robust discrete-space representations. ARAE jointly trains both a rich discrete-space encoder, such as an RNN, and a simpler continuous space generator function, while using generative adversarial network (GAN) training to constrain the distributions to be similar. This method yields a smoother contracted code space that maps similar inputs to nearby codes, and also an implicit latent variable GAN model for generation. Experiments on text and discretized images demonstrate that the GAN model produces clean interpolations and captures the multimodality of the original space, and that the autoencoder produces improve- ments in semi-supervised learning as well as state-of-the-art results in unaligned text style transfer task using only a shared continuous-space representation.

##### Abstract (translated by Google)
虽然自动编码器是连续结构（如图像或波形）表示学习的关键技术，但是为离散结构（如文本序列或离散图像）开发通用自动编码器已被证明是更具挑战性的。特别是，离散输入使得学习一个平滑编码器变得更加困难，该编码器保留了输入空间中复杂的局部关系。在这项工作中，我们提出了一个对抗正则化的自动编码器（ARAE），目标是学习更强大的离散空间表示。 ARAE联合训练一个丰富的离散空间编码器，如一个RNN和一个简单的连续空间发生器功能，同时使用生成对抗网络（GAN）训练来约束分布类似。这种方法产生一个更平滑的合约代码空间，将相似的输入映射到附近的代码，并且还产生一个隐式潜在变量GAN模型。对文本和离散化图像的实验表明，GAN模型产生干净的插值并捕获原始空间的多模态，并且自动编码器在半监督学习中产生了改进，在未对齐的文本中产生了最新的结果风格转移任务只使用共享的连续空间表示。

##### URL
[https://arxiv.org/abs/1706.04223](https://arxiv.org/abs/1706.04223)

##### PDF
[https://arxiv.org/pdf/1706.04223](https://arxiv.org/pdf/1706.04223)

