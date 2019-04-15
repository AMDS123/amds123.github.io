---
layout: post
title: "Examining the Mapping Functions of Denoising Autoencoders in Music Source Separation"
date: 2019-04-12 11:22:43
categories: arXiv_SD
tags: arXiv_SD Knowledge
author: Stylianos Ioannis Mimilakis, Konstantinos Drossos, Estefan&#xed;a Cano, Gerald Schuller
mathjax: true
---

* content
{:toc}

##### Abstract
The goal of this work is to investigate what music source separation approaches based on neural networks learn from the data. We examine the mapping functions of neural networks that are based on the denoising autoencoder (DAE) model, and conditioned on the mixture magnitude spectra. For approximating the mapping functions, we propose an algorithm that is inspired by the knowledge distillation and is denoted as the neural couplings algorithm (NCA). The NCA yields a matrix that expresses the mapping of the mixture to the target source magnitude information. Using the NCA we examine the mapping functions of three fundamental DAE models in music source separation; one with single layer encoder and decoder, one with multi-layer encoder and single layer decoder, and one using the skip-filtering connections (SF) with a single encoding and decoding layer. We first train these models with realistic data to estimate the singing voice magnitude spectra from the corresponding mixture. We then use the optimized models and test spectral data as input to the NCA. Our experimental findings show that approaches based on the DAE model learn scalar filtering operators, exhibiting a predominant diagonal structure in their corresponding mapping functions, limiting the exploitation of inter-frequency structure of music data. In contrast, skip-filtering connections are shown to assist the DAE model in learning filtering operators that exploit richer inter-frequency structure.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.06157](http://arxiv.org/abs/1904.06157)

##### PDF
[http://arxiv.org/pdf/1904.06157](http://arxiv.org/pdf/1904.06157)

