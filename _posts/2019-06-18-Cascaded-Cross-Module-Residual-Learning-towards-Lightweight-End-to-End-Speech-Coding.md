---
layout: post
title: "Cascaded Cross-Module Residual Learning towards Lightweight End-to-End Speech Coding"
date: 2019-06-18 19:11:14
categories: arXiv_SD
tags: arXiv_SD
author: Kai Zhen, Jongmo Sung, Mi Suk Lee, Seungkwon Beack, Minje Kim
mathjax: true
---

* content
{:toc}

##### Abstract
Speech codecs learn compact representations of speech signals to facilitate data transmission. Many recent deep neural network (DNN) based end-to-end speech codecs achieve low bitrates and high perceptual quality at the cost of model complexity. We propose a cross-module residual learning (CMRL) pipeline as a module carrier with each module reconstructing the residual from its preceding modules. CMRL differs from other DNN-based speech codecs, in that rather than modeling speech compression problem in a single large neural network, it optimizes a series of less-complicated modules in a two-phase training scheme. The proposed method shows better objective performance than AMR-WB and the state-of-the-art DNN-based speech codec with a similar network architecture. As an end-to-end model, it takes raw PCM signals as an input, but is also compatible with linear predictive coding (LPC), showing better subjective quality at high bitrates than AMR-WB and OPUS. The gain is achieved by using only 0.9 million trainable parameters, a significantly less complex architecture than the other DNN-based codecs in the literature.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.07769](http://arxiv.org/abs/1906.07769)

##### PDF
[http://arxiv.org/pdf/1906.07769](http://arxiv.org/pdf/1906.07769)

