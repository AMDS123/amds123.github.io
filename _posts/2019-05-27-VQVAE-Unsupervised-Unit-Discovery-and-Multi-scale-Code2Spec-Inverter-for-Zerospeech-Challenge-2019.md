---
layout: post
title: "VQVAE Unsupervised Unit Discovery and Multi-scale Code2Spec Inverter for Zerospeech Challenge 2019"
date: 2019-05-27 18:59:54
categories: arXiv_CL
tags: arXiv_CL Adversarial
author: Andros Tjandra, Berrak Sisman, Mingyang Zhang, Sakriani Sakti, Haizhou Li, Satoshi Nakamura
mathjax: true
---

* content
{:toc}

##### Abstract
We describe our submitted system for the ZeroSpeech Challenge 2019. The current challenge theme addresses the difficulty of constructing a speech synthesizer without any text or phonetic labels and requires a system that can (1) discover subword units in an unsupervised way, and (2) synthesize the speech with a target speaker's voice. Moreover, the system should also balance the discrimination score ABX, the bit-rate compression rate, and the naturalness and the intelligibility of the constructed voice. To tackle these problems and achieve the best trade-off, we utilize a vector quantized variational autoencoder (VQ-VAE) and a multi-scale codebook-to-spectrogram (Code2Spec) inverter trained by mean square error and adversarial loss. The VQ-VAE extracts the speech to a latent space, forces itself to map it into the nearest codebook and produces compressed representation. Next, the inverter generates a magnitude spectrogram to the target voice, given the codebook vectors from VQ-VAE. In our experiments, we also investigated several other clustering algorithms, including K-Means and GMM, and compared them with the VQ-VAE result on ABX scores and bit rates. Our proposed approach significantly improved the intelligibility (in CER), the MOS, and discrimination ABX scores compared to the official ZeroSpeech 2019 baseline or even the topline.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.11449](https://arxiv.org/abs/1905.11449)

##### PDF
[https://arxiv.org/pdf/1905.11449](https://arxiv.org/pdf/1905.11449)

