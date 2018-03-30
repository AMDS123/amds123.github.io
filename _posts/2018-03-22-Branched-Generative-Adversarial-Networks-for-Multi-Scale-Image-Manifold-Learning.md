---
layout: post
title: "Branched Generative Adversarial Networks for Multi-Scale Image Manifold Learning"
date: 2018-03-22 17:07:32
categories: arXiv_CV
tags: arXiv_CV Image_Caption Adversarial GAN
author: Zili Yi, Zhiqin Chen, Hao Zhang, Xin Huang, Minglun Gong
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce BranchGAN, a novel training method that enables unconditioned generative adversarial networks (GANs) to learn image manifolds at multiple scales. What is unique about BranchGAN is that it is trained in multiple branches, progressively covering both the breadth and depth of the network, as resolutions of the training images increase to reveal finer-scale features. Specifically, each noise vector, as input to the generator network, is explicitly split into several sub-vectors, each corresponding to and trained to learn image representations at a particular scale. During training, we progressively "de-freeze" the sub-vectors, one at a time, as a new set of higher-resolution images is employed for training and more network layers are added. A consequence of such an explicit sub-vector designation is that we can directly manipulate and even combine latent (sub-vector) codes that are associated with specific feature scales. Experiments demonstrate the effectiveness of our training method in multi-scale, disentangled learning of image manifolds and synthesis, without any extra labels and without compromising quality of the synthesized high-resolution images. We further demonstrate two new applications enabled by BranchGAN.

##### Abstract (translated by Google)
我们引入了BranchGAN，一种新颖的训练方法，使无条件的生成对抗网络（GAN）能够在多个尺度上学习图像流形。 BranchGAN的独特之处在于它在多个分支进行了培训，随着培训图像分辨率的增加，逐渐覆盖网络的广度和深度，以显示更精细的特征。具体而言，作为输入到发生器网络的每个噪声向量被明确地分成几个子向量，每个子向量对应于并且被训练以学习特定尺度的图像表示。在训练过程中，我们逐步“逐步”去除子矢量，因为一组新的高分辨率图像被用于训练，并增加了更多的网络层。这种明确的子矢量指定的结果是，我们可以直接操纵甚至组合与特定特征尺度关联的潜在（子矢量）代码。实验证明了我们的训练方法在图像流形和合成的多尺度，解题学习中的有效性，没有任何额外的标签，并且不会损害合成的高分辨率图像的质量。我们进一步演示了BranchGAN启用的两个新应用程序。

##### URL
[https://arxiv.org/abs/1803.08467](https://arxiv.org/abs/1803.08467)

##### PDF
[https://arxiv.org/pdf/1803.08467](https://arxiv.org/pdf/1803.08467)

