---
layout: post
title: "Analysis of DNN Speech Signal Enhancement for Robust Speaker Recognition"
date: 2018-11-19 11:41:23
categories: arXiv_SD
tags: arXiv_SD Recognition
author: Ondrej Novotny, Oldrich Plchot, Ondrej Glembek, Jan &quot;Honza&quot; Cernocky, Lukas Burget
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we present an analysis of a DNN-based autoencoder for speech enhancement, dereverberation and denoising. The target application is a robust speaker verification (SV) system. We start our approach by carefully designing a data augmentation process to cover wide range of acoustic conditions and obtain rich training data for various components of our SV system. We augment several well-known databases used in SV with artificially noised and reverberated data and we use them to train a denoising autoencoder (mapping noisy and reverberated speech to its clean version) as well as an x-vector extractor which is currently considered as state-of-the-art in SV. Later, we use the autoencoder as a preprocessing step for text-independent SV system. We compare results achieved with autoencoder enhancement, multi-condition PLDA training and their simultaneous use. We present a detailed analysis with various conditions of NIST SRE 2010, 2016, PRISM and with re-transmitted data. We conclude that the proposed preprocessing can significantly improve both i-vector and x-vector baselines and that this technique can be used to build a robust SV system for various target domains.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.07629](http://arxiv.org/abs/1811.07629)

##### PDF
[http://arxiv.org/pdf/1811.07629](http://arxiv.org/pdf/1811.07629)

