---
layout: post
title: "Non-Parallel Voice Conversion with Cyclic Variational Autoencoder"
date: 2019-07-24 00:37:20
categories: arXiv_CL
tags: arXiv_CL Relation
author: Patrick Lumban Tobing, Yi-Chiao Wu, Tomoki Hayashi, Kazuhiro Kobayashi, Tomoki Toda
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a novel technique for a non-parallel voice conversion (VC) with the use of cyclic variational autoencoder (CycleVAE)-based spectral modeling. In a variational autoencoder(VAE) framework, a latent space, usually with a Gaussian prior, is used to encode a set of input features. In a VAE-based VC, the encoded latent features are fed into a decoder, along with speaker-coding features, to generate estimated spectra with either the original speaker identity (reconstructed) or another speaker identity (converted). Due to the non-parallel modeling condition, the converted spectra can not be directly optimized, which heavily degrades the performance of a VAE-based VC. In this work, to overcome this problem, we propose to use CycleVAE-based spectral model that indirectly optimizes the conversion flow by recycling the converted features back into the system to obtain corresponding cyclic reconstructed spectra that can be directly optimized. The cyclic flow can be continued by using the cyclic reconstructed features as input for the next cycle. The experimental results demonstrate the effectiveness of the proposed CycleVAE-based VC, which yields higher accuracy of converted spectra, generates latent features with higher correlation degree, and significantly improves the quality and conversion accuracy of the converted speech.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.10185](http://arxiv.org/abs/1907.10185)

##### PDF
[http://arxiv.org/pdf/1907.10185](http://arxiv.org/pdf/1907.10185)

