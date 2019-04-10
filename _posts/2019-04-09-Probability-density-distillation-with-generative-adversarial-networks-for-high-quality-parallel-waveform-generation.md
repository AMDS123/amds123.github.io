---
layout: post
title: "Probability density distillation with generative adversarial networks for high-quality parallel waveform generation"
date: 2019-04-09 05:38:18
categories: arXiv_SD
tags: arXiv_SD Adversarial GAN Optimization
author: Ryuichi Yamamoto, Eunwoo Song, Jae-Min Kim
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes an effective probability density distillation (PDD) algorithm for WaveNet-based parallel waveform generation (PWG) systems. Recently proposed teacher-student frameworks in the PWG system have successfully achieved a real-time generation of speech signals. However, the difficulties optimizing the PDD criteria without auxiliary losses result in quality degradation of synthesized speech. To generate more natural speech signals within the teacher-student framework, we propose a novel optimization criterion based on generative adversarial networks (GANs). In the proposed method, the inverse autoregressive flow-based student model is incorporated as a generator in the GAN framework, and jointly optimized by the PDD mechanism with the proposed adversarial learning method. As this process encourages the student to model the distribution of realistic speech waveform, the perceptual quality of the synthesized speech becomes much more natural. Our experimental results verify that the PWG systems with the proposed method outperform both those using conventional approaches, and also autoregressive generation systems with a well-trained teacher WaveNet.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.04472](http://arxiv.org/abs/1904.04472)

##### PDF
[http://arxiv.org/pdf/1904.04472](http://arxiv.org/pdf/1904.04472)

