---
layout: post
title: "CycleGAN-VC2: Improved CycleGAN-based Non-parallel Voice Conversion"
date: 2019-04-09 12:55:35
categories: arXiv_SD
tags: arXiv_SD Adversarial GAN
author: Takuhiro Kaneko, Hirokazu Kameoka, Kou Tanaka, Nobukatsu Hojo
mathjax: true
---

* content
{:toc}

##### Abstract
Non-parallel voice conversion (VC) is a technique for learning the mapping from source to target speech without relying on parallel data. This is an important task, but it has been challenging due to the disadvantages of the training conditions. Recently, CycleGAN-VC has provided a breakthrough and performed comparably to a parallel VC method without relying on any extra data, modules, or time alignment procedures. However, there is still a large gap between the real target and converted speech, and bridging this gap remains a challenge. To reduce this gap, we propose CycleGAN-VC2, which is an improved version of CycleGAN-VC incorporating three new techniques: an improved objective (two-step adversarial losses), improved generator (2-1-2D CNN), and improved discriminator (PatchGAN). We evaluated our method on a non-parallel VC task and analyzed the effect of each technique in detail. An objective evaluation showed that these techniques help bring the converted feature sequence closer to the target in terms of both global and local structures, which we assess by using Mel-cepstral distortion and modulation spectra distance, respectively. A subjective evaluation showed that CycleGAN-VC2 outperforms CycleGAN-VC in terms of naturalness and similarity for every speaker pair, including intra-gender and inter-gender pairs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.04631](http://arxiv.org/abs/1904.04631)

##### PDF
[http://arxiv.org/pdf/1904.04631](http://arxiv.org/pdf/1904.04631)

