---
layout: post
title: "Classical Music Generation in Distinct Dastgahs with AlimNet ACGAN"
date: 2019-01-15 08:00:27
categories: arXiv_SD
tags: arXiv_SD Adversarial QA GAN
author: Saber Malekzadeh, Maryam Samami, Shahla RezazadehAzar, Maryam Rayegan
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper AlimNet (With respect to great musician, Alim Qasimov) an auxiliary generative adversarial deep neural network (ACGAN) for generating music categorically, is used. This proposed network is a conditional ACGAN to condition the generation process on music tracks which has a hybrid architecture, composing of different kind of layers of neural networks. The employed music dataset is MICM which contains 1137 music samples (506 violins and 631 straw) with seven types of classical music Dastgah labels. To extract both temporal and spectral features, Short-Time Fourier Transform (STFT) is applied to convert input audio signals from time domain to time-frequency domain. GANs are composed of a generator for generating new samples and a discriminator to help generator making better samples. Samples in time-frequency domain are used to train discriminator in fourteen classes (seven Dastgahs and two instruments). The outputs of the conditional ACGAN are also artificial music samples in those mentioned scales in time-frequency domain. Then the output of the generator is transformed by Inverse STFT (ISTFT). Finally, randomly ten generated music samples (five violin and five straw samples) are given to ten musicians to rate how exact the samples are and the overall result was 76.5%.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1901.04696](https://arxiv.org/abs/1901.04696)

##### PDF
[https://arxiv.org/pdf/1901.04696](https://arxiv.org/pdf/1901.04696)

