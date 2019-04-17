---
layout: post
title: "Unsupervised acoustic unit discovery for speech synthesis using discrete latent-variable neural networks"
date: 2019-04-16 09:38:01
categories: arXiv_CL
tags: arXiv_CL CNN
author: Ryan Eloff, Andr&#xe9; Nortje, Benjamin van Niekerk, Avashna Govender, Leanne Nortje, Arnu Pretorius, Elan van Biljon, Ewald van der Westhuizen, Lisa van Staden, Herman Kamper
mathjax: true
---

* content
{:toc}

##### Abstract
For our submission to the ZeroSpeech 2019 challenge, we apply discrete latent-variable neural networks to unlabelled speech and use the discovered units for speech synthesis. Unsupervised discrete subword modelling could be useful for studies of phonetic category learning in infants or in low-resource speech technology requiring symbolic input. We use an autoencoder (AE) architecture with intermediate discretisation. We decouple acoustic unit discovery from speaker modelling by conditioning the AE's decoder on the training speaker identity. At test time, unit discovery is performed on speech from an unseen speaker, followed by unit decoding conditioned on a known target speaker to obtain reconstructed filterbanks. This output is fed to a neural vocoder to synthesise speech in the target speaker's voice. For discretisation, categorical variational autoencoders (CatVAEs), vector-quantised VAEs (VQ-VAEs) and straight-through estimation are compared at different compression levels on two languages. Our final model uses convolutional encoding, VQ-VAE discretisation, deconvolutional decoding and an FFTNet vocoder. We show that decoupled speaker conditioning intrinsically improves discrete acoustic representations, yielding competitive synthesis quality compared to the challenge baseline.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.07556](http://arxiv.org/abs/1904.07556)

##### PDF
[http://arxiv.org/pdf/1904.07556](http://arxiv.org/pdf/1904.07556)

