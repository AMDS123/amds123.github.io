---
layout: post
title: "Theoretical limitations of Encoder-Decoder GAN architectures"
date: 2017-11-07 18:30:24
categories: arXiv_CV
tags: arXiv_CV GAN Inference
author: Sanjeev Arora, Andrej Risteski, Yi Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Encoder-decoder GANs architectures (e.g., BiGAN and ALI) seek to add an inference mechanism to the GANs setup, consisting of a small encoder deep net that maps data-points to their succinct encodings. The intuition is that being forced to train an encoder alongside the usual generator forces the system to learn meaningful mappings from the code to the data-point and vice-versa, which should improve the learning of the target distribution and ameliorate mode-collapse. It should also yield meaningful codes that are useful as features for downstream tasks. The current paper shows rigorously that even on real-life distributions of images, the encode-decoder GAN training objectives (a) cannot prevent mode collapse; i.e. the objective can be near-optimal even when the generated distribution has low and finite support (b) cannot prevent learning meaningless codes for data -- essentially white noise. Thus if encoder-decoder GANs do indeed work then it must be due to reasons as yet not understood, since the training objective can be low even for meaningless solutions.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1711.02651](https://arxiv.org/abs/1711.02651)

##### PDF
[https://arxiv.org/pdf/1711.02651](https://arxiv.org/pdf/1711.02651)

