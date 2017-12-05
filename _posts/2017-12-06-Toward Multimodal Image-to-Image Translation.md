---
layout: post
title: 'Toward Multimodal Image-to-Image Translation'
date: 2017-12-06 02:21:09
categories: arXiv_CV
tags: arXiv_CV
author: Jun-Yan Zhu, Richard Zhang, Deepak Pathak, Trevor Darrell, Alexei A. Efros, Oliver Wang, Eli Shechtman
---

* content
{:toc}

##### Abstract
Many image-to-image translation problems are ambiguous, as a single input image may correspond to multiple possible outputs. In this work, we aim to model a \emph{distribution} of possible outputs in a conditional generative modeling setting. The ambiguity of the mapping is distilled in a low-dimensional latent vector, which can be randomly sampled at test time. A generator learns to map the given input, combined with this latent code, to the output. We explicitly encourage the connection between output and the latent code to be invertible. This helps prevent a many-to-one mapping from the latent code to the output during training, also known as the problem of mode collapse, and produces more diverse results. We explore several variants of this approach by employing different training objectives, network architectures, and methods of injecting the latent code. Our proposed method encourages bijective consistency between the latent encoding and output modes. We present a systematic comparison of our method and other variants on both perceptual realism and diversity.

##### Abstract (translated by Google)
许多图像到图像的转换问题是不明确的，因为单个输入图像可能对应于多个可能的输出。在这项工作中，我们的目标是在一个有条件的生成建模环境中模拟一个可能的输出的分布。映射的模糊性是在低维的潜在向量中进行的，可以在测试时间随机采样。生成器学习将给定的输入与此潜在代码结合起来映射到输出。我们明确地鼓励输出和潜在代码之间的联系是可逆的。这有助于防止训练期间从潜在代码到输出的多对一映射（也称为模式崩溃问题），并产生更多不同的结果。我们通过采用不同的培训目标，网络体系结构和注入潜在代码的方法来探索这种方法的几种变体。我们提出的方法鼓励潜在的编码和输出模式之间的双射一致性。我们提出了一个系统的比较我们的方法和感知现实主义和多样性的其他变种。

##### URL
[https://arxiv.org/abs/1711.11586](https://arxiv.org/abs/1711.11586)

