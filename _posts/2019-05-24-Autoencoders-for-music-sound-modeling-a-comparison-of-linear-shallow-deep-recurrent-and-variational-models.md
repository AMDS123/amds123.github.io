---
layout: post
title: "Autoencoders for music sound modeling: a comparison of linear, shallow, deep, recurrent and variational models"
date: 2019-05-24 08:30:50
categories: arXiv_SD
tags: arXiv_SD Regularization Optimization RNN
author: Fanny Roche (1 and 2), Thomas Hueber (1), Samuel Limier (2), Laurent Girin (1 and 3) ((1) Univ. Grenoble Alpes, CNRS, Grenoble INP, GIPSA-lab, Grenoble, France, (2) Arturia, Meylan, France, (3) INRIA, Perception Team, Montbonnot, France)
mathjax: true
---

* content
{:toc}

##### Abstract
This study investigates the use of non-linear unsupervised dimensionality reduction techniques to compress a music dataset into a low-dimensional representation which can be used in turn for the synthesis of new sounds. We systematically compare (shallow) autoencoders (AEs), deep autoencoders (DAEs), recurrent autoencoders (with Long Short-Term Memory cells -- LSTM-AEs) and variational autoencoders (VAEs) with principal component analysis (PCA) for representing the high-resolution short-term magnitude spectrum of a large and dense dataset of music notes into a lower-dimensional vector (and then convert it back to a magnitude spectrum used for sound resynthesis). Our experiments were conducted on the publicly available multi-instrument and multi-pitch database NSynth. Interestingly and contrary to the recent literature on image processing, we can show that PCA systematically outperforms shallow AE. Only deep and recurrent architectures (DAEs and LSTM-AEs) lead to a lower reconstruction error. The optimization criterion in VAEs being the sum of the reconstruction error and a regularization term, it naturally leads to a lower reconstruction accuracy than DAEs but we show that VAEs are still able to outperform PCA while providing a low-dimensional latent space with nice "usability" properties. We also provide corresponding objective measures of perceptual audio quality (PEMO-Q scores), which generally correlate well with the reconstruction error.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1806.04096](http://arxiv.org/abs/1806.04096)

##### PDF
[http://arxiv.org/pdf/1806.04096](http://arxiv.org/pdf/1806.04096)

