---
layout: post
title: "Unsupervised Speech Domain Adaptation Based on Disentangled Representation Learning for Robust Speech Recognition"
date: 2019-04-12 07:55:53
categories: arXiv_CL
tags: arXiv_CL Adversarial GAN Speech_Recognition Represenation_Learning Recognition
author: Jong-Hyeon Park, Myungwoo Oh, Hyung-Min Park
mathjax: true
---

* content
{:toc}

##### Abstract
In general, the performance of automatic speech recognition (ASR) systems is significantly degraded due to the mismatch between training and test environments. Recently, a deep-learning-based image-to-image translation technique to translate an image from a source domain to a desired domain was presented, and cycle-consistent adversarial network (CycleGAN) was applied to learn a mapping for speech-to-speech conversion from a speaker to a target speaker. However, this method might not be adequate to remove corrupting noise components for robust ASR because it was designed to convert speech itself. In this paper, we propose a domain adaptation method based on generative adversarial nets (GANs) with disentangled representation learning to achieve robustness in ASR systems. In particular, two separated encoders, context and domain encoders, are introduced to learn distinct latent variables. The latent variables allow us to convert the domain of speech according to its context and domain representation. We improved word accuracies by 6.55~15.70\% for the CHiME4 challenge corpus by applying a noisy-to-clean environment adaptation for robust ASR. In addition, similar to the method based on the CycleGAN, this method can be used for gender adaptation in gender-mismatched recognition.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.06086](http://arxiv.org/abs/1904.06086)

##### PDF
[http://arxiv.org/pdf/1904.06086](http://arxiv.org/pdf/1904.06086)

