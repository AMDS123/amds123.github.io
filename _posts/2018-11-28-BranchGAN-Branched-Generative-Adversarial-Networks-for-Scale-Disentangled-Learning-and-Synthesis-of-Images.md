---
layout: post
title: "BranchGAN: Branched Generative Adversarial Networks for Scale-Disentangled Learning and Synthesis of Images"
date: 2018-11-28 20:14:26
categories: arXiv_CV
tags: arXiv_CV Image_Caption Adversarial GAN
author: Zili Yi, Zhiqin Chen, Hao Cai, Xin Huang, Minglun Gong, Hao Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce BranchGAN, a novel training method that enables unconditioned generative adversarial networks (GANs) to learn image manifolds at multiple scales. The key novel feature of BranchGAN is that it is trained in multiple branches, progressively covering both the breadth and depth of the network, as resolutions of the training images increase to reveal finer-scale features. Specifically, each noise vector, as input to the generator network, is explicitly split into several sub-vectors, each corresponding to, and is trained to learn, image representations at a particular scale. During training, we progressively de-freeze the sub-vectors, one at a time, as a new set of higher-resolution images is employed for training and more network layers are added. A consequence of such an explicit sub-vector designation is that we can directly manipulate and even combine latent (sub-vector) codes which model different feature scales. Experiments demonstrate the effectiveness of our training method in scale-disentangled learning of image manifolds and synthesis, without any extra labels and without compromising quality of the synthesized high-resolution images. We further demonstrate three applications enabled or improved by BranchGAN.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1803.08467](http://arxiv.org/abs/1803.08467)

##### PDF
[http://arxiv.org/pdf/1803.08467](http://arxiv.org/pdf/1803.08467)

