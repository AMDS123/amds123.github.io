---
layout: post
title: "A Deep Generative Model of Speech Complex Spectrograms"
date: 2019-03-08 03:57:30
categories: arXiv_SD
tags: arXiv_SD CNN
author: Aditya Arie Nugraha, Kouhei Sekiguchi, Kazuyoshi Yoshii
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes an approach to the joint modeling of the short-time Fourier transform magnitude and phase spectrograms with a deep generative model. We assume that the magnitude follows a Gaussian distribution and the phase follows a von Mises distribution. To improve the consistency of the phase values in the time-frequency domain, we also apply the von Mises distribution to the phase derivatives, i.e., the group delay and the instantaneous frequency. Based on these assumptions, we explore and compare several combinations of loss functions for training our models. Built upon the variational autoencoder framework, our model consists of three convolutional neural networks acting as an encoder, a magnitude decoder, and a phase decoder. In addition to the latent variables, we propose to also condition the phase estimation on the estimated magnitude. Evaluated for a time-domain speech reconstruction task, our models could generate speech with a high perceptual quality and a high intelligibility.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.03269](http://arxiv.org/abs/1903.03269)

##### PDF
[http://arxiv.org/pdf/1903.03269](http://arxiv.org/pdf/1903.03269)

