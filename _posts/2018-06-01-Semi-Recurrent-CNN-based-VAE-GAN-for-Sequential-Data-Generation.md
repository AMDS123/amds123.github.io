---
layout: post
title: "Semi-Recurrent CNN-based VAE-GAN for Sequential Data Generation"
date: 2018-06-01 18:59:58
categories: arXiv_CV
tags: arXiv_CV GAN Relation
author: Mohammad Akbari, Jie Liang
mathjax: true
---

* content
{:toc}

##### Abstract
A semi-recurrent hybrid VAE-GAN model for generating sequential data is introduced. In order to consider the spatial correlation of the data in each frame of the generated sequence, CNNs are utilized in the encoder, generator, and discriminator. The subsequent frames are sampled from the latent distributions obtained by encoding the previous frames. As a result, the dependencies between the frames are maintained. Two testing frameworks for synthesizing a sequence with any number of frames are also proposed. The promising experimental results on piano music generation indicates the potential of the proposed framework in modeling other sequential data such as video.

##### Abstract (translated by Google)
介绍了一种用于生成时序数据的半经常性混合VAE-GAN模型。为了考虑生成序列的每个帧中的数据的空间相关性，在编码器，发生器和鉴别器中使用CNN。随后的帧从通过对先前帧进行编码而获得的潜在分布中采样。结果，帧之间的依赖关系得以保持。还提出了两种用于合成具有任意数量的帧的序列的测试框架。有关钢琴音乐生成的有希望的实验结果表明，该建议框架在建模其他连续数据（如视频）时具有潜力。

##### URL
[https://arxiv.org/abs/1806.00509](https://arxiv.org/abs/1806.00509)

##### PDF
[https://arxiv.org/pdf/1806.00509](https://arxiv.org/pdf/1806.00509)

